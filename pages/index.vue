<template>
    <main class="max-w-xl m-auto">
        <div class=" sticky top-0 -z-50 flex flex-col items-center min-h-screen p-12 gap-12">
            <h1 class="text-4xl font-bold text-center">HAPPY MAKDOONG!</h1>
            <img src="~/assets/image/makdoong.png" data-aos="fade-up" data-aos-anchor-placement="top-bottom" alt="막둥이" loading="lazy">
        </div>
        <div class="bg-pink-200 rounded-t-lg flex flex-col items-center min-h-screen p-12 gap-12">
            <h1 class="text-4xl font-bold text-center" data-aos="fade-up">우리집 귀염둥이 서막둥</h1>
            <img src="~/assets/image/babymakdoong.png"  data-aos="fade-up" alt="새끼 시절 막둥이" loading="lazy">
            <p class="text-2xl text-center" data-aos="fade">지금 인스타그램에서 막둥이를 만나보세요!</p>
            <svg class="w-12 h-12 mb-24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g><g id="SVGRepo_iconCarrier"> <path d="M12 4V20M12 20L8 16M12 20L16 16" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path> </g></svg>
        </div>
    </main>
    <div class="fixed bottom-0 left-0 right-0 p-2 max-w-xl m-auto w-full">
        <NuxtLink class="bg-gradient-to-tr from-pink-500 to-purple-500 text-white font-bold p-3 rounded-lg w-full flex justify-center items-center text-center text-xl hover:brightness-95 hover:scale-95 transition-all duration-300 print:hidden" href="https://www.instagram.com/makdoong.kr">instargram</NuxtLink>
    </div>
</template>
<script setup lang="ts">
useSeoMeta({
  title: 'Makdoong Cat',
  ogTitle: 'Makdoong Cat',
  description: '우리집 고양이 막둥이 이야기',
  ogDescription: '우리집 고양이 막둥이 이야기',
  ogImage: 'https://makdoong.kr/og.png',
  twitterCard: 'summary_large_image',
})
</script>