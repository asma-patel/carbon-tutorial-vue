<template>
  <div id="app">
    <tutorial-header />
    <cv-content id="#main-content">
<cv-content id="#main-content">
  <router-view />
</cv-content>
    </cv-content>
  </div>
</template>
<script>
import TutorialHeader from "./components/TutorialHeader";

export default {
  name: "App",
  components: {
    TutorialHeader
  }
};
</script>
