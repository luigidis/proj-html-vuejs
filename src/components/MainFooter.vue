<template>
    <div>
        <CommunityBanner />
        <FooterLists />
        <ContactUs />
    </div>
</template>

<script>
import CommunityBanner from './CommunityBanner.vue';
import FooterLists from './FooterLists.vue';
import ContactUs from './ContactUs.vue';

export default {
    name: "MainFooter",
    components: { CommunityBanner, FooterLists, ContactUs }
}
</script>

<style lang="scss" scoped>

</style>