<template>
  <div class="home">
    <HelloWorld msg="Teste VUE Vercel App - Versão 2" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld
  }
};
</script>
