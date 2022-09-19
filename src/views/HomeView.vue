<template>
  <div class="home">
    <HeaderShayna/>
    <HeroShayna/>
    <WomanShayna/>
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShayna from '@/components/HeaderShayna.vue'
import HeroShayna from '@/components/HeroShayna.vue'
import WomanShayna from '@/components/WomanShayna.vue'


export default {
  name: 'HomeView',
  components: {
    HeaderShayna,
    HeroShayna,
    WomanShayna
  }
}
</script>
