<template>
  <h1>I AM OFFICE COMPONENT</h1>
  <button @click="goToHome">Go To Home</button>
</template>

<script>
export default {
 methods:{
  goToHome(){
    this.$router.push("/")
  }
 }
}
</script>

<style>

</style>