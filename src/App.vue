<script>

  import Title from "./components/AppTitle.vue";
  import Jumbo from "./components/AppHero.vue";

  export default{
    data() {
      return{

      };
    },

    components: {
      Title,
      Jumbo,
    },

    methods: {

    },
  }
</script>

<template>
  <div id="body">

    <Title></Title>

    <Jumbo></Jumbo>

  </div>
</template>

<style>

#body{
  height: 100vh;
  
  background-color: black;
}

</style>
