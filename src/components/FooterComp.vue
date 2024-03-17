<script setup>

</script>

<template>
  <footer class="info-loja" v-if="showFooter">
    <h1 class="infofooter">Informações da empresa:</h1>
    <h2 class="infofooter">dLSDFNKGLDNÇK</h2>
  </footer>
</template>

<style scoped>
.info-loja {
  background-color: #6d686867;
  color: rgb(255, 255, 255);
  text-align: center;
  padding: 10rem;
  width: 80%;
   
}
@media only screen and (max-width: 767px) {
    #rodape {
        display: none; 
    }
}
.infofooter {
  color: white;
}


</style>
