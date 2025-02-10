<template>
  <!-- logo -->
  <nuxt-link to="/">
    <img
        class="h-[30px] sm:h-[32px] z-20 sm:relative absolute sm:left-0 sm:translate-x-0 transition duration-500"
        :class="[
          { invert: isInvert || !isCollapse },
          !isCollapse ? 'left-4 translate-x-0' : 'left-1/2 -translate-x-1/2',
          useRoute().path !== '/coverage' || !isCollapse ? '' : 'hidden sm:block',
        ]"
        src="/logo.webp"
        alt="UGLOSS"
    />
  </nuxt-link>
</template>

<script setup>
import { usePageNavigation } from "@/hooks/usePageNavigation";

const { currentPage, isInScrollPage } = usePageNavigation();

const isInvert = computed(() => {
  return isInScrollPage && (currentPage.value === 7 || currentPage.value === 3);
});

const isCollapse = ref(true);

</script>

<style scoped>
.aaa{
  pointer-events: auto;
}
</style>
