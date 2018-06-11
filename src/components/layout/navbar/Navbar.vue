<template>
  <vs-topbar class="nav" style="justify-content: flex-end;">
    <span class="brand left">Brand</span>
    <ul class="items">
      <li class="menu-item"><a href="#">MENU</a></li>
      <li class="menu-item"><a href="#">MENU</a></li>
      <li class="menu-item"><a href="#">MENU</a></li>
      <li class="menu-item"><a href="#">MENU</a></li>
    </ul>
  </vs-topbar>
</template>

<script>

export default {
  name: 'navbar'
}
</script>

<style lang="scss" scoped>
  .nav {
    padding-right: 15px;
    padding-top: 20px;
  }
  .brand {
    margin-left: 30px;
    margin-right: auto;
  }
  .menu-item {
    display: inline-block;
    margin-right: 15px;
    margin-left: 15px;

    a {
      color: #2e2e2e;
      font-weight: 500;
    }
    :hover {
      color: #308f30;
    }
  }
</style>
