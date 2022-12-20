<template>
 
  <img src="https://mdbootstrap.com/img/new/slides/041.jpg" class="w-full h-auto" alt="..." />

</template>

<script>
export default {
  name: "Index",
  mounted() {
    this.$router.push('/home')
  }
};
</script>

<style>
body {
  font-family: 'Poppins', sans-serif;
}
</style>
