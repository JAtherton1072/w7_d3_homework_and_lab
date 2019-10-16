<template lang="html">
  <div class="country-details">
    <h3>Name: {{country.name}}</h3>
    <p>Captial: {{country.capital}}</p>
    <p>Population: {{country.population}}</p>
    <img class="lrg-flag" :src="country.flag" />


  </div>
</template>

<script>
export default {
  name:'country-detail',
  props:['country']
}
</script>

<style lang="css" scoped>

.lrg-flag {
  height: 100px
}
.country-details {
height: 300px;
width: 300px;
border: solid coral;
text-align: center;

}

</style>
