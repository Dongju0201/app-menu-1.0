<template>
  <div id="app">
   app
 <Header></Header>
 <router-view></router-view>
  </div>
</template>

<script>

import Header from 'components/Header'
export default {

  name: 'App',
  "Header":Header
  
}
</script>

<style>

</style>
