<template>
<b-container class="">
  <b-jumbotron header="Bootstrap Vue" lead="VueJs-BootStrap Boiler Plate">
  <p>{{msg}}</p>
  <b-btn variant="primary" href="#">More Info</b-btn>
</b-jumbotron>
</b-container>


</template>

<script>
export default {
  name: 'MainPage',
  props: {
    msg: String
  }
}
</script>

