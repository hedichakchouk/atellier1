<script setup>
import Personne from "./components/Personne.vue";
import User from "./components/User.vue";
import ListLivre from "./components/ListLivre.vue";
</script>
<template>
  <h1>Bienvenu dans notre site</h1>
  <Personne/>
  <user/>
  <list-livre/>
</template>

<style scoped>
h1{
  font-family: 'sans-serif';
  font-size: 23px;
}
</style>
