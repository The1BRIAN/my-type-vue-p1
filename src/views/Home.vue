<template>
  <div class="home">
    <Udemy title="Welcome to Your Vue.js + TypeScript App"/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src
import Udemy from "@/components/UdemyTut.vue"; // @ is an alias to /src
@Component({
  components: {
    HelloWorld,
    Udemy
  }
})
export default class Home extends Vue {}
</script>
