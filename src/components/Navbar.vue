<template>
  <nav class="bg-blue-500 p-4">
    <div class="container mx-auto flex justify-between items-center">
      <!-- Logo ou Nome do Site -->
      <router-link to="/" class="text-white text-xl font-bold">
        Meu Portfólio
      </router-link>

      <!-- Lista de Links -->
      <ul class="flex space-x-4 list-none p-0 m-0">
        <li>
          <router-link to="/" class="text-white hover:text-gray-200">
            Início
          </router-link>
        </li>
        <li>
          <router-link to="/about" class="text-white hover:text-gray-200">
            Sobre
          </router-link>
        </li>
        <li>
          <router-link to="/projects" class="text-white hover:text-gray-200">
            Projetos
          </router-link>
        </li>
        <li>
          <router-link to="/contact" class="text-white hover:text-gray-200">
            Contato
          </router-link>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Navbar',
};
</script>