<template>
  <vs-topbar style="justify-content: flex-end;">
    <div class="content">
      <ul class="items-right">
        <li><a href="#">MENU</a></li>
        <li><a href="#">MENU</a></li>
        <li><a href="#">MENU</a></li>
        <li><a href="#">MENU</a></li>
      </ul>
    </div>
  </vs-topbar>
</template>

<script>

export default {
  name: 'navbar'
}
</script>

<style lang="scss" scoped>
  .content {
    padding-right: 15px;
    padding-top: 20px;
  }
  li {
    display: inline-block;
    margin-right: 15px;
    margin-left: 15px
  }
  li a {
    color: #2e2e2e;
    font-weight: 500;
  }
</style>
