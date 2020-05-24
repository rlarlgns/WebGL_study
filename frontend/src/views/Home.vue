<template>
  <div class="home">
    <WebGL />
  </div>
</template>

<script>
// @ is an alias to /src
import WebGL from "@/components/webgl.vue";

export default {
  name: "Home",
  components: {
    WebGL
  }
};
</script>
