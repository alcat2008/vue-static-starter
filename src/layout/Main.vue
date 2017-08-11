<template>
  <div class="container">
    <img src="../assets/logo.png">

    <ul>
      <li>
        <nav-tab href="/">Home</nav-tab>
        <nav-tab href="/foo">Foo</nav-tab>
        <nav-tab href="/bar">Bar</nav-tab>
        <nav-tab href="/about">About</nav-tab>
      </li>
    </ul>

    <slot></slot>
  </div>
</template>


<script>
  import NavTab from '../components/NavTab.vue'

  export default {
    components: {
      NavTab
    }
  }
</script>

<style>
.container {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
