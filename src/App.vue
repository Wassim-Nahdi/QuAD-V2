<template>
  <div class="appDiv">
    <navbar />
    <signup />
    <!-- <profile /> -->
  </div>
</template>

<script>
import signup from "./components/signup.vue";
import navbar from "./components/navbar.vue";
// import profile from './components/Freelancer/profile.vue'

export default {
  name: "App",
  components: {
    signup,
    navbar,
    // profile
  },
};
</script>

<style scoped>
.appDiv {
  background-image: linear-gradient( rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5) ), url("https://cdn.mos.cms.futurecdn.net/kVHndERw4LxuWxArZouVU6.jpg");
;
  background-size: cover;
  height: 805px;
  font-family: "Varela Round", sans-serif;
}
</style>
