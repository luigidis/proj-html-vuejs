<template>
  <div>
    <HeroSection/>
    <LatestNewsSec/>
    <ForumSection/>
  </div>
</template>

<script>
import HeroSection from './HeroSection.vue'
import LatestNewsSec from './LatestNewsSec.vue'
import ForumSection from './ForumSection.vue'

export default {
  name: 'MainContainer',
  props: {

  },
  components: {
    HeroSection,
    LatestNewsSec,
    ForumSection,
}
}
</script>


<style scoped lang="scss">

</style>
