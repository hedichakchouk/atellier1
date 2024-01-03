<template>
  <div>
    <p> Email : {{user.email}}</p>
    <p> adresse : {{user.adresse}}</p>
    <p> tel : {{user.tel}}</p>
    <button class="btn btn-success" @click="modif" > modifier </button>
  </div>
</template>

<script setup>
import {ref} from "vue";
const user = ref({
  email:"iit@gmail.com",
  adresse:"sfax" ,
  tel:"+216 22336483"
})
const modif= ()=> {user.value.email ='sfaxxxt@gmail.com'}

</script>

<style lang="scss" scoped>

</style>