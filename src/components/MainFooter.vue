<template>
    <div>
        <CommunityBanner />
        <FooterLists />
    </div>
</template>

<script>
import CommunityBanner from './CommunityBanner.vue';
import FooterLists from './FooterLists.vue';

export default {
    name: "MainFooter",
    components: { CommunityBanner, FooterLists }
}
</script>

<style lang="scss" scoped>

</style>