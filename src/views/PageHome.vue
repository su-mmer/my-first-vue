<!-- PageHome.vue -->
<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Hi, I'm Hyeonhee Kim !!!!"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'  // 기존 Helloworld 끌고 옴 

export default {
  name: 'PageHome',
  components: {  // components 폴더 하위에 존재하는 애 끌고옴 
    HelloWorld
  }
}
</script>