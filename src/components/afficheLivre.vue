<template>
  <div>
<Inscription/>
    <table class="table table-striped">
      <thead>
      <tr>
        <th>Isbn</th>
        <th>Titre</th>
        <th>Auteur</th>
        <th>Annedition</th>
        <th>Prix</th>
        <th>Couverture</th>
        <th>Action</th>
      </tr>
      </thead>
      <tbody>
      <tr v-for="liv in props.livres" :key="liv.id">
        <td>{{liv.isbn}}</td>
        <td>{{liv.titre}}</td>
        <td>{{liv.auteur}}</td>
        <td>{{liv.annedition}}</td>
        <td>{{liv.prix}}</td>
        <td> <img :src="liv.couverture" width ="80" height="80"/> </td>
        <td><button class="btn btn-warning" >Modifer</button></td>
      </tr>
      </tbody>
    </table>
  </div>
</template>

<script setup>
import Inscription from "./Inscription.vue";

const props = defineProps(['livres'])
</script>

<style lang="scss" scoped>

</style>

