<template>
  <div class="layout">
    <navbar></navbar>
    <div class="footer">
      ©2018. Todos os direitos reservados.&nbsp;<a href="http://canionlabs.io" target="_blank">CanionLabs </a>
    </div>
  </div>
</template>

<script>
import Navbar from './navbar/Navbar'

export default {
  name: 'layout',
  components: {
    Navbar
  }
}
</script>

<style lang='scss'>
  .footer {
    padding-top:25px;
    position: absolute;
    bottom: 0;
    padding-bottom: 8px;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }
</style>
