<template lang="pug">
#guitar
  h1 近期活動公告
  router-link(to='/') 回社團介紹首頁
  router-link(to='/guitar') 吉他社社史
  router-link(to='/guitar/learning') 教學活動
</template>

<script>
export default {
  naame: 'Guitar'
}
</script>
