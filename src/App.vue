<template>
<div>

  <SchoolMainpage />
  <WebBody/>
  <EventContainer/>
  <FooterContainer/>
 
  


</div>

</template>

<script>

import SchoolMainpage from './components/SchoolMainpage.vue'
import WebBody from './components/WebBody.vue';
import EventContainer from './components/EventContainer.vue';
import FooterContainer from './components/FooterContainer.vue'

export default {
  name: 'App',
  components: {

    SchoolMainpage,
    WebBody,
    EventContainer,
    FooterContainer
  
  }
}
</script>

<style>
#app {
  
}
</style>
