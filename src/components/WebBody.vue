<template>
  <div class="container-fluid main-body">
    <div class="Main-haiding">
        <h3>LDPS In Numbers</h3>
        <hr class="line-below">
    </div>
   <child-component></child-component>
   <child-componentcard></child-componentcard>
   <child-nevigator></child-nevigator>
   


  </div>
</template>

<script>
import ChildComponet from './ChildComponet.vue'
import ChildComponentcard from './ChildComponentcard.vue';
import NevigatorComponent from './NevigatorComponent.vue';

export default {
    components: {
    'child-component': ChildComponet,
    'child-componentcard':ChildComponentcard,
    'child-nevigator':NevigatorComponent
  },

}
</script>

<style>
.Main-haiding{
    text-align: center;
}
.main-body{
    height: 1610px;
    flex-shrink: 0; 
    background:linear-gradient(180deg, rgba(181, 46, 46, 0.54) 20.45%, rgba(157, 52, 52, 0.00) 120.09%, rgba(157, 52, 52, 0.00) 120.1%, #CA2828 120.11%);


}
.line-below{
    height: 6px;
    border-width: 0px;
    color: gray;
    background-color: #eae2e2;
    align-items: center;
    width: 28%;
    align-content: center;
    margin-left: 37%;
    stroke-width: 4px;
stroke: #000;

filter: blur(2px);
}
</style>