<template>
  <div class="flex h-screen bg-white">
    <!-- Lado esquerdo -->
    <div class="w-[600px] bg-teal-700">
      <!-- left side page -->
      
      <!-- Modal fixo -->
      <div class="fixed top-1/2 left-[100px] -translate-y-1/2">
        <div class="h-[600px] w-[500px] bg-teal-500 py-20 px-40 shadow-lg rounded-lg">
          <h3 class="text-2xl text-center font-bold mb-4">Sign In</h3>
          <p class="mb-4 text-center">tela modal login</p>
          <button class="px-4 py-2 bg-white text-teal-700 rounded">Sign In</button>
        </div>
      </div>

    </div>

    <!-- Lado direito -->
    <div class="relative flex-1">
      <img 
        src="@/assets/images/imagem-fundo-2.jpg" 
        alt="fundo"
        class="w-full h-full object-cover"
      />


      <!-- Gradiente por cima da imagem -->
      <div class="absolute inset-0 bg-gradient-to-r from-teal-700 to-transparent"></div>
    </div>
  </div>
</template>
