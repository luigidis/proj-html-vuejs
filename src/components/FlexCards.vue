<template>
    <div class="flex_cards d-flex">
        <div class="big_card col-8">
            <div class="card_content">

                <p class="intro">REVIEWED PRODUCT</p>
                <h3>Mauris viverra atisan ipsum eget felis prims efficitur varius</h3>
                <p class="paragraph">
                    In quis lectus sed leo elementum faucibus in dapibus dictum Nullamolestie tortor nec lectus
                    venenatis,
                    sed blandit dui,dolor at bibendum.
                </p>
                <div class="button_black">
                    <a href="#">
                        Read More
                        <font-awesome-icon icon="fa-solid fa-angle-right" />
                    </a>
                </div>
            </div>
        </div>
        <div class="multi_cards col-4 d-flex flex-column">
            <div class="title_mine">
                <h3>Tutorials & Guides</h3>
            </div>
            <div class="card_mine col-12 d-flex mt_1">
                <figure>
                    <img src="../assets/img/post_feat_img_23-147x118.jpg" alt="">
                </figure>
                <article>
                    <h4>DonecOrnare pretium</h4>
                    <div class="date">Ovtober 11th,2015 | Comments Off</div>
                </article>
            </div>
            <div class="card_mine col-12 d-flex">
                <figure>
                    <img src="../assets/img/post_feat_img_23-147x118.jpg" alt="">
                </figure>
                <article>
                    <h4>DonecOrnare pretium</h4>
                    <div class="date">Ovtober 11th,2015 | Comments Off</div>
                </article>
            </div>
            <div class="card_mine col-12 d-flex">
                <figure>
                    <img src="../assets/img/post_feat_img_23-147x118.jpg" alt="">
                </figure>
                <article>
                    <h4>DonecOrnare pretium</h4>
                    <div class="date">Ovtober 11th,2015 | Comments Off</div>
                </article>
            </div>
        </div>
    </div>
</template>






<script>
export default {
    name: 'FlexCards'
}
</script>

<style lang="scss" scoped>
@import '../styles/variables.scss';

.flex_cards {
    // height: 480px;
    gap: 30px;

    .big_card {
        background-image: url(../assets/img/featured_article_2_bg.jpg);
        background-position: center;
        background-repeat: no-repeat;
        background-size: 100% 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;

        .card_content {
            color: white;
            max-width: 570px;
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

    .multi_cards {
        .title_mine {
            padding-bottom: 32px;
            position: relative;
        }

        .title_mine::after {
            content: "";
            width: 80px;
            height: 3px;
            background-color: salmon;
            position: absolute;
            bottom: 0;
            left: 0;

        }

        .card_mine {
            gap: 25px;
            

            figure {
                max-width: 138px;
            }
        }
    }

    .mt_1 {
        margin-top: 40px;
    }
    


}
</style>
