<script setup>
import CardVue from "../components/Card.vue";

  components: { CardVue }
</script>

<template>
  <div class="w-full h-screen container-all font-rubik">
    <div class="container flex flex-col items-center mx-auto pt-16">
      <h1 class="text-white text-xl">Cartão de embarque</h1>
      <card-vue/>
      <span class="text-white text-sm">Qualquer problema procure o balcão de atendimento da sua companhia aérea</span>

    </div>
  </div>
</template>
<style scoped>
.container-all {
 background: linear-gradient(167.96deg, #8257E5 0%, #271A45 100%);
}
</style>

