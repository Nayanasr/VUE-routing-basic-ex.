<template>
   <h1>I AM HOME COMPONENT</h1>
   <button @click="goToOffice">Go to Office</button>
</template>

<script>
export default {
  methods: {
   goToOffice(){
      // console.log("executed");
      this.$router.push("/office")
      // this.$router.back()
      // this.$router.forward()
   }
  }
}
</script>

<style>

</style>