<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/perfect-.jpg" />
    <HelloWorld msg="Enter text" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "home",
  components: {
    HelloWorld
  }
};
</script>
<style scoped>
img {
  width: 200px;
}
</style>