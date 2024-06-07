<template>
  <div>
    <NuxtPage/>
  </div>
</template>
<script setup>
const route = useRoute()
useHead(() => ({
  link: [
    {
      rel: 'canonical',
      href: 'https://makdoong.kr' + route.path,
    },
  ],
  meta: [
    {
      name: 'naver-site-verification',
      content: '70ac51c1045ed1618cdebbd84d300a31d1b59c27'
    },
  ]
}))
</script>