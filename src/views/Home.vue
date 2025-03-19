<template>
    <div>
      <Navbar />
      <main class="container mx-auto p-4">
        <h1 class="text-3xl font-bold mb-4">Bem-vindo ao Meu Portfólio</h1>
        <p class="text-lg">Aqui você encontrará meus projetos e habilidades como desenvolvedor full stack.</p>
      </main>
      <Footer />
    </div>
  </template>
  
  <script>
  import Navbar from '../components/Navbar.vue';
  import Footer from '../components/Footer.vue';
  
  export default {
    components: {
      Navbar,
      Footer,
    },
  };
  </script>