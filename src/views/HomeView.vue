<script setup lang="ts">
</script>

<template>
  <div class="bg-slate-900 min-h-screen">
    <div class="relative flex flex-col py-4 bg-sky-950 text-amber-50 overflow-hidden"
      style="clip-path: polygon(0 0, 100% 0, 100% 70%, 0 100%)">

      <!-- imagem overlay -->
      <img src="../assets/camera_one.webp"
        class="absolute inset-0 w-full h-full object-cover opacity-90 mix-blend-soft-light " />

      <!-- conteúdo -->
      <h1 class="relative z-10 text-[15vw] font-black leading-none tracking-tighter">
        FELIPE ALVES
      </h1>

      <div class="relative z-10 flex flex-col px-5">
        <div class="self-start text-[8vw]">
          Filmmaker
        </div>
      </div>
    </div>
    <hr class="my-12 h-0.5 border-t-0 bg-neutral-100 dark:bg-white/10" />
    <div class="flex text-6xl min-w-screen text-center text-amber-50">
        Seu produto com cara de cinema
    </div>
    <hr class="my-12 h-0.5 border-t-0 bg-neutral-100 dark:bg-white/10" />


    
  </div>
  
</template>