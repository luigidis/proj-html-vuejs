<template>
    <div class="bg_shark">
        <a :href="link.link">
            {{link.text}}
            <font-awesome-icon icon="fa-solid fa-arrow-right" class="ps-2 fs_1"></font-awesome-icon>
        </a>
    </div>
</template>
        

<script>
export default {
    name: 'BottomComponent',
    props: {
        link: Object,
    }

}
</script>

<style lang="scss" scoped>
@import '../styles/variables.scss';

.bg_shark {
    background-color: $shark-color;
    color: white;
    text-transform: uppercase;
    height: 150px;
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 18px;
    font-weight: bold;
    .fs_1 {
        font-size: 14px;
    }
    
}
</style>