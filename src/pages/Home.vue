<template>
  <div class="home">
    <img
      alt="Vue logo" 
      src="@/assets/logo/light-mode-logo.png" 
      width="380"
      height="380"
    />
    <HelloWorld msg="Welcome to my world :)" />
    <HelloWorld msg="coming soon" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
  },
};
</script>
