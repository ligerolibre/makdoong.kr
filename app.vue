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
    {
      name: 'norton-safeweb-site-verification',
      content: 'FU1NZGZGFFA-W5AHND4CPV79FIF9D0GOM6C8E9HWS1G6RKDUXFK3DI5717EKIKAPB7XOEYRTPER64X0TA6A1M9MJBOLAVKHVBYB1F5X97K2SVE5GHHUCK31DVZI1H615'
    },
  ]
}))
</script>