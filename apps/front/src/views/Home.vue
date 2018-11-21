<template>
  <div class="home">
    <Logo></Logo>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Logo from '@/svg/Logo.vue'

export default {
  name: 'home',
  components: {
    HelloWorld,
    Logo
  }
}
</script>
