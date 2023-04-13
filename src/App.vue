<script>

import MyHeader from './components/MyHeader.vue'
import MyMainTop from './components/MyMainTop.vue'
import MyMainBottom from './components/MyMainBottom.vue'
import MyFooter from './components/MyFooter.vue'
import { createApp } from 'vue'

export default{
  
  components:{
    MyHeader,
    MyMainTop,
    MyMainBottom,
    MyFooter

  }

}
</script>

<template>



 <MyHeader home="Home" blog="Blog" features="Features" courses="Courses" shop="Shop" page="Page"/>
 <MyMainTop/>
 <MyMainBottom/>
 <MyFooter titleone="Address" titletwo="Explore" titlethree="Information"/>


</template>

<style>


</style>
