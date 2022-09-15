<template>
    <div class="single_card">
        <div class="card_content">
            <p class="intro">Feature Article</p>
            <h3>Cras Malesuada et orci eget pharetra</h3>
            <p class="paragraph">
                In quis lectus sed leo elementum faucibus in dapibus dictum Nullamolestie tortor nec lectus venenatis,
                sed blandit dui,dolor at bibendum sadips ets ipsums dolores ficilis uns leo lectus.
            </p>
            <div class="button_black">
                <a href="#">
                    Read More
                    <font-awesome-icon icon="fa-solid fa-angle-right" />
                </a>
            </div>
        </div>
    </div>
</template>



<script>
export default {
    name: 'SingleCard'
}
</script>

<style lang="scss" scoped>
@import '../styles/variables.scss';

.single_card {
    background-image: url(../assets/img/featured_article_1_bg.jpg);
    background-position: center;
    background-repeat: no-repeat;
    background-size: contain;
    height: 573px;
    color: white;
    display: flex;
    align-items: center;
    
    .card_content {
        max-width: 960px;
        margin: 0 auto;
        .intro {
            letter-spacing: 5px;
            text-transform: uppercase;
            font-size: 12px;
            font-weight: bold;
        }

        h3 {
            font-weight: bold;
        }

        .paragraph {
            font-size: 14px;
            font-weight: bold;
        }

        .button_black {
            padding: 10px 20px;
            background-color: $shark-color;
            width: 190px;
            text-align: center;
            font-weight: bold;
            text-transform: uppercase;
        }
    }
}



</style>