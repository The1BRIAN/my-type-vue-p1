<template>
    <div>{{title}}
        <div>{{another}}</div>
    </div>
</template>

<script>
export default {
  name: "landing",
  data() {
    return {
      greetingsMessage: "Hello from data",
      another:"This is another message"
    };
  },
  methods: {
    sayHelo: function() {
      return this.greetingsMessage;
    }
  },
  watch: {},
  computed: {},
  props: {
    title: ""
  }
};
</script>

<style>
</style>

