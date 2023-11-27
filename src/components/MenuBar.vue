<template>
    <div class="fixed flex h-20 w-screen items-center justify-around bg-red-900 shadow-sm max-[780px]:text-sm">
      <a href="https://www.riotgames.com/pt-br" target="blank"><img src="../assets/riot 2.png" class="w-28 bg-red-950 rounded-2xl shadow-md hover:bg-slate-100 cursor-pointer"></a>
      <ul class="flex text-white gap-10 font-mono font-semibold text-xl max-[780px]:hidden">
        <li><a href="#nossahistoria" class="p-2 hover:bg-gray-800/40 rounded-full">Nossa História</a></li>
        <li><a href="#noticia" class="p-2 hover:bg-gray-800/40 rounded-full">Notícia</a></li>
        <li><a href="#portfolio" class="p-2 hover:bg-gray-800/40 rounded-full">Portfólio</a></li>
        <li><a href="#comunicacao" class="p-2 hover:bg-gray-800/40 rounded-full">Comunicação</a></li>
        <li><a href="#faleconosco" class="p-2 hover:bg-gray-800/40 rounded-full">Fale Conosco</a></li>
      </ul>
      <img src="../assets/TFT Pingu impressionado.png" class="w-32 pb-2 align-bottom">
    </div>
</template>

<script>

import { defineComponent } from 'vue';

export default defineComponent({
    name: 'MenuBar',
})

</script>

<style scoped>


@media only screen and (max-width: 768px) {
  ul {
    gap: 5px
  }
}

</style>