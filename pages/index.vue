<template>
  <div>
    <Slider class="container--fluid" />
    <Index class="container mt-3" />
  </div>
</template>

<script>
import Slider from './Slider/index'
import Index from './Index/index'

export default {
  components:{
    Slider,
    Index
  }
}
</script>