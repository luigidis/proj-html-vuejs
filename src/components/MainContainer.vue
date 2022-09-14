<template>
  <div>
    <FirstSection/>
    <LatestNewsSec/>
    <ForumSection/>
  </div>
</template>

<script>
import FirstSection from './FirstSection.vue'
import LatestNewsSec from './LatestNewsSec.vue'
import ForumSection from './ForumSection.vue'

export default {
  name: 'MainContainer',
  props: {

  },
  components: {
    FirstSection,
    LatestNewsSec,
    ForumSection,
}
}
</script>


<style scoped lang="scss">

</style>
