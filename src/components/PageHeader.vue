<!-- PageHeader.vue -->
<template>
  <header>
    <h1>
      <router-link to ="/">Secure Wifi 점검 현황</router-link> 
    </h1>
    <div id="nav">
      <router-link to="/">점검 현황</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/board/list">게시판</router-link>
    </div>
  </header>
  <hr />  <!--가로줄-->
</template>

<script>
export default {
}
</script>

<style scoped>
</style>