<!-- Composant principal -->

<template>
    <div>
        <img :src="img">
        <h1> Hello {{ person.firstname }} {{ person.lastname }} de {{ from }} !</h1>
    </div>
</template>

<script>
export default{
  data () {

  },
  props: ['firstname', 'lastname', 'from']
}

</script>

<style>
</style>
