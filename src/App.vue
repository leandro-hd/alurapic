<template>
  <div>
    <h1>{{ titulo }}</h1>

    <ul>
      <li v-for="foto of fotos">
        <img :src="foto.url" :alt="foto.titulo">
      </li>
    </ul>
  </div>
</template>

<script>
export default {

  data() {
    return {
      titulo: 'Alurapic',
      fotos: [
        {
          url: 'https://conteudo.imguol.com.br/c/entretenimento/54/2020/04/28/cachorro-pug-1588098472110_v2_900x506.jpg.webp',
          titulo: 'Cachorro'
        },
        {
          url: 'https://conteudo.imguol.com.br/c/entretenimento/54/2020/04/28/cachorro-pug-1588098472110_v2_900x506.jpg.webp',
          titulo: 'Cachorrão'
        }
      ]
    }
  }

}
</script>

<style>

</style>
