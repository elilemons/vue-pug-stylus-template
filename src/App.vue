<template lang="pug">
  .hero.is-warning.is-bold.is-fullheight
    .hero-body
        .container
          HelloWorld.title.is-1
</template>

<script>
import './styles/typography.styl';
import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",
  components: {
    HelloWorld
  }
};
</script>
