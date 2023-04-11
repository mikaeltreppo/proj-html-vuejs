<script>

import MyHeader from './components/MyHeader.vue'
import MyMain from './components/MyMain.vue'
import MyFooter from './components/MyFooter.vue'

export default{
  components:{
    MyHeader,
    MyMain,
    MyFooter

  }

}
</script>

<template>

<div class="mainContainer">

 <MyHeader/>
 <MyMain/>
 <MyFooter/>

</div>

</template>

<style>
.mainContainer{
  width: 80%;
  margin: auto;

}
</style>
