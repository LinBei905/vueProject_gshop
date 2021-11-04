<template>
  <div>
    <h1>Header</h1>
    <div>
      <router-link to="/">home</router-link>
      <router-link to="/search">search</router-link>
      <router-link to="/register">register</router-link>
      <router-link to="/login">login</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="less" scoped>
</style>