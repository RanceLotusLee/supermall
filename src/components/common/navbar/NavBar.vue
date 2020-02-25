<template>
  <div class="nav-bar">
    <div class="left">
      <slot></slot>
    </div>
    <div class="center">
      <slot></slot>
    </div>
    <div class="right">
      <slot></slot>
    </div>
 
  </div>
</template>
<script>
export default {
  name: 'NavBar'
}
</script>

<style scoped>
.nav-bar {
  display: flex;
  height: 44px;
  line-height: 44px;
}

.left ,.right{
  width: 46px;
  background-color: aqua;
}

.center {
  flex: 1;
  text-align: center;
  background-color: red;
}
</style>