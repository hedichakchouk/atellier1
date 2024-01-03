
<script setup>
import {ref} from "vue";

const nom = ref("Hedi") ;
const age = ref(24) ;


</script>

<template>
  <div>
 <h1> votre nom est :{{nom}}</h1>
 <h1> votre age est :{{age}}</h1>
  </div>
</template>

<style lang="css" scoped>

</style>
