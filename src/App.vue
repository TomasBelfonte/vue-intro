<script>
  export default {
    data () {
      return {
        messaggio: "hello vite"
      };
    }
  };
</script>

<template>
<h1>{{ messaggio }}</h1>
<p class="lead" >Ecco il mio primo progeto in vite</p>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
