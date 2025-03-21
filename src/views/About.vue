<template>
  <div>
    <h1 class="text-3xl font-bold underline">
      Sobre Mim
    </h1>
    <p class="mt-4">Aqui você encontrará informações sobre mim e minha experiência.</p>
    
    <!-- Botão "Voltar" -->
    <button
      @click="goBack"
      class="mt-4 bg-blue-500 text-white px-4 py-2 rounded hover:bg-blue-600"
    >
      Voltar
    </button>
  </div>
</template>

<!-- =============================================================== -->

<script>
export default {
  name: 'About',
  methods: {
    goBack() {
      this.$router.go(-1); // voltar para home
    },
  },
};
</script>