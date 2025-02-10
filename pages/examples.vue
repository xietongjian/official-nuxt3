<template>
  <div class="fixed left-0 top-0 w-full h-[68px] bg-black"></div>
  <main class="pt-[68px] bg-[#FAFAFA] text-[#666] text-sm leading-7">
    <div class="pb-[100px] pt-[60px] px-6 w-auto xl:w-[1030px] mx-auto">
      <h1 class="text-3xl font-semibold mb-6 text-[#333]">UGLOSS 用户协议</h1>
      <p class="mb-6">
        欢迎使用UGLOSS平台提供的服务，《UGLOSS用户协议》（以下简称“本协议”）是您（或称“用户”，指注册、登录及使用本服务的个人或组织）与UGLOSS平台运营公司之间关于UGLOSS（简称“本平台”)与UGLOSS提供的产品、程序及服务所订立的协议。<br />
      </p>

      <h1 class="text-3xl font-semibold mb-6 text-[#333]">UGLOSS 用户协议</h1>
      <p>
        欢迎使用UGLOSS平台提供的服务，《UGLOSS用户协议》（以下简称“本协议”）是您（或称“用户”，指注册、登录及使用本服务的个人或组织）与UGLOSS平台运营公司之间关于UGLOSS（简称“本平台”)与UGLOSS提供的产品、程序及服务所订立的协议。<br />
        【审慎阅读】UGLOSS在此特别提醒您认真阅读、充分理解本协议中各条款，特别是免除或者限制责任的条款、法律适用和管辖条款，尤此类条款将以加粗的形式提示。UGLOSS平台的法律声明、平台规范、通知、公告、针对个别商品或服务所公示的规则等均为本协议的组成部分，与本协议不可分割且具有同等法律效力。
        如您同意本协议并完成全部注册程序，即表示您已充分阅读、理解并接受本协议的全部内容，并与UGLOSS之间达成一致，成为UGLOSS用户。阅读本协议的过程中，如果您不同意本协议或其中任何条款约定，您应立即停止访问UGLOSS网站和/或使用UGLOSS服务。
      </p>
    </div>
    <Copyright class="pt-9 pb-16 border-t-2 border-black" />
  </main>
</template>

<script setup>
import Copyright from "~/components/Copyright.vue";

definePageMeta({
  title: "用户协议",
});

// onMounted(() => {
//   document.querySelector("nav").classList.add("sm:mix-blend-difference");
// });

// onUnmounted(() => {
//   document.querySelector("nav").classList.remove("sm:mix-blend-difference");
// });
</script>
