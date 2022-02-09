<template>
  <div class="page">
    <!-- <Intro /> -->
    <!-- <Hello /> -->
    <!-- <Portfolio /> -->
    <Reviews />
  </div>
</template>

<script>
// import Intro from '@/components/Intro.vue'
// import Hello from '@/components/Hello.vue'
// import Portfolio from '@/components/Portfolio.vue'
import Reviews from '@/components/Reviews.vue'
export default {
  name: 'Home',
  components: {
      // Intro,
      // Hello,
      // Portfolio,
      Reviews
  }
}
</script>


<style scoped lang="scss">
.page {
  width: 1350px;
  background-color: aquamarine;
  margin: 0 auto;
}
</style>
