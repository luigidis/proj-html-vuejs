<template>
  <div>
    <HeroSection />
    <LatestNewsSec />
    <ForumSection />
    <BottomComponent :link="link_1"/>
  </div>
</template>





<script>
import HeroSection from './HeroSection.vue'
import LatestNewsSec from './LatestNewsSec.vue'
import ForumSection from './ForumSection.vue'
import BottomComponent from './BottomComponent.vue'

export default {
  name: 'MainContainer',
  props: {

  },
  components: {
    HeroSection,
    LatestNewsSec,
    ForumSection,
    BottomComponent
  },
  data() {
      return {
        link_1: {
          text: 'Go to our forum',
          link: '#'
        },
      }
    },
}
</script>


<style scoped lang="scss">

</style>
