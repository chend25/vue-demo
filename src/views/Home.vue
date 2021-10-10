<!--
 * @Author: your name
 * @Date: 2021-10-08 22:45:43
 * @LastEditTime: 2021-10-10 17:54:42
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \vue-demo\src\views\Home.vue
-->
<template>
  <div class="home">
    <img
      alt="Vue logo"
      src="../assets/logo.png"
    >
    <hello-world
      msg="Welcome to Your Vue.js App"
      :is-temp-msg="isTempMsg"
    />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld';

export default {
  name: 'Home',
  components: {
    HelloWorld,
  },
  data() {
    return {
      isTempMsg: '',
    };
  },
};
</script>
