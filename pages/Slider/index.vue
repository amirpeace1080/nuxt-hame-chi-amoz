<template>
  <v-carousel hide-delimiters height="340px" class="radi">
    <v-carousel-item
      v-for="(item,i) in items"
      :key="i"
      :src="item.src"
    ></v-carousel-item>
  </v-carousel>
</template>

<script>
  export default {
    data () {
      return {
        items: [
          {
            src: "https://znbl.ir/image/1968/mainSlide"
          },
          {
            src: 'https://znbl.ir/image/1946/mainSlide',
          },
          {
            src: 'https://znbl.ir/image/1967/mainSlide',
          },
          {
            src: 'https://znbl.ir/image/1958/mainSlide',
          },
          {
            src: 'https://znbl.ir/image/1959/mainSlide'
          },
        ],
      }
    },
  }
</script>

<style scoped>
  .radi{
    border-radius: 8px;
  }
</style>