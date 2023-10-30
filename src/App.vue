<template>
<div>

  <SchoolMainpage />
  <WebBody/>


</div>

</template>

<script>

import SchoolMainpage from './components/SchoolMainpage.vue'
import WebBody from './components/WebBody.vue';
export default {
  name: 'App',
  components: {

    SchoolMainpage,
    WebBody
  }
}
</script>

<style>
#app {
  
}
</style>
