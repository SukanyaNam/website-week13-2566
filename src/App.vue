<template>
  <div>
    <router-link :to= "{name: 'Home'}">Home</router-link>
    <router-link :to="{name:'About'}">About</router-link>
  </div>
  <router-view />
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>