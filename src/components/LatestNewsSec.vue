<template>
    <div class="news_container container">
        <div class="title_news">
            <h3>Phasellus Eget Metus</h3>
            <h2>All the latest news</h2>
        </div>
        <TripleCards class="mb_1"/>
        <SingleCard class="mb_1"/>
        <TripleCards class="mb_1"/>
        <FlexCards />
        <BottomComponent :link="link_1"/>
    </div>
</template>

<script>
import TripleCards from './TripleCards.vue'
import SingleCard from './SingleCard.vue'
import FlexCards from './FlexCards.vue'
import BottomComponent from './BottomComponent.vue'

export default {
    name: 'LatestNewsSec',
    components: {
    TripleCards,
    SingleCard,
    FlexCards,
    BottomComponent
},
    data() {
        return {
            link_1: {
                text: 'Read our blog',
                link: '#'
            }
        }
    },
    
}
</script>

<style lang="scss" scoped>
@import '../styles/variables.scss';

.news_container {
    padding-top: 115px;
    .title_news {
        position: relative;
        margin-bottom: 45px;
        h3 {
            text-transform: uppercase;
            font-size: 12px;
            text-align: center;
            font-weight: bold;
            letter-spacing: 5px;
            padding-bottom: 25px;
            color: $capeCod-color;
        }
        h2 {
            font-weight: bold;
            font-size: 42px;
            letter-spacing: 2%;
            text-align: center;
            padding-bottom: 42px;
        }
    }
    .title_news::after {
        content: "";
        width: 80px;
        height: 3px;
        background-color: salmon;
        position: absolute;
        bottom: 0;
        left: 50%;
        transform: translate(-50%, -50%)
    }
    .pb_1 {
        padding-bottom: 54px;
    }
    .mb_1 {
        margin-bottom: 76px;
    }
}
</style>
       
        
    