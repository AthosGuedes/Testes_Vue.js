<template>
  <div class="flex h-screen bg-white">
    <!-- Lado esquerdo -->
    <div class="w-[600px] bg-teal-700">
      <!-- left side page -->
      
      <!-- Modal fixo -->
      <div class="fixed top-1/2 left-[100px] -translate-y-1/2">
        <div class="h-[600px] w-[500px] bg-teal-500 pt-12 pb-20 px-40 shadow-lg rounded-lg flex flex-col items-center justify-center">
          <div>
            <div className="mb-5 flex flex-col items-center justify-center">
              <img 
                src="@/assets/images/logo-png-2.png" 
                alt="logo"
                className="w-[120px] h-[120px]"
              />
            </div>
            <h3 class="text-4xl text-center font-bold mb-4 text-white">Sign In</h3>
            <label className="text-sm">E-mail:  </label>
            <input className="bg-white mb-6 mt-px w-[320px] h-11 text-zinc-200 shadow-md rounded-md"></input>
            <label className="text-sm">Password:  </label>
            <input className="bg-white mb-6 mt-px w-[320px] h-11 text-zinc-200 shadow-md rounded-md"></input>
            <button class="px-4 py-2 w-[320px] bg-amber-600 text-black rounded shadow-lg text-black">Sign In</button>
          </div>
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
