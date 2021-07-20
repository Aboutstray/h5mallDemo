<template>
  <div id="app">
    <tabber>
      <tabber-item>
        <img slot="tabber-icon" src="./assets/img/tabber/shouye1@2x.png" alt="">
        <img slot="tabber-icon-active" src="./assets/img/tabber/shouye@2x.png" alt="">
        <div slot="tabber-text">首页</div>
      </tabber-item>
      <tabber-item>
        <img slot="tabber-icon" src="./assets/img/tabber/shouye1@2x.png" alt="">
        <img slot="tabber-icon-active" src="./assets/img/tabber/shouye@2x.png" alt="">
        <div slot="tabber-text">首页</div>
      </tabber-item>
      <tabber-item>
        <img slot="tabber-icon" src="./assets/img/tabber/shouye1@2x.png" alt="">
        <img slot="tabber-icon-active" src="./assets/img/tabber/shouye@2x.png" alt="">
        <div slot="tabber-text">首页</div>
      </tabber-item>
      <tabber-item>
        <img slot="tabber-icon" src="./assets/img/tabber/shouye1@2x.png" alt="">
        <img slot="tabber-icon-active" src="./assets/img/tabber/shouye@2x.png" alt="">
        <div slot="tabber-text">首页</div>
      </tabber-item>
    </tabber>
  </div>
</template>

<script>

import Tabber from './components/common/tabber/Tabber'
import TabberItem from './components/common/tabber/Tabberitem'

export default {
  name: 'App',
  components:{
    Tabber,
    TabberItem
  }
}
</script>

<style>
</style>
