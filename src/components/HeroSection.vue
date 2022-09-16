<template>
    <div class="slider">
        <div class="hero">
            <div class="text_container container">
                <h1>Tech Forum!</h1>
                <p>Discuss all the latest technology news and tends</p>
                <a href="#" class="button">
                    Get Avada Now!
                    <font-awesome-icon :icon="['fas', 'angle-right']"/>
                </a>

            </div>
        </div>
        <div class="bottom_hero">
            <h3> Ava Forum is the palce to be</h3>
            <p>
                In quis lectus sed leo elementum faucibus in dapibus dictum. <br>
                Nulla molestie tortor nec lectus venenatis, sed blandit dui finibus. <br>
                Dolor at,bibendum purus. Donex vehicula nec tortor ac finibus. <br>
            </p>
        </div>
    </div>
</template>

<script>
export default {
    name: 'FirstSection',
}
</script>

<style lang="scss" scoped>
@import '../styles/variables.scss';

.slider {
    background-image: url(../assets/img/home_slider_bg.jpg);
    background-repeat: no-repeat;
    background-position: top;
    background-size: 100% 853px;
    background-attachment: fixed;
    .hero {
        height: 840px;
        display: flex;
        justify-content: center;
        flex-direction: column;

        .text_container {
            color: white;

            h1 {
                font-size: 120px;
                font-weight: bold;
            }

            p {
                padding-top: 55px;
                padding-bottom: 45px;
                font-size: 20px;
            }

            .button {
                text-transform: uppercase;
                background-color: $easternBlue-color;
                font-size: 14px;
                font-weight: bold;
                padding: 15px 30px;
                max-width: 235px;
                text-align: center;
            }
        }
    }


    .bottom_hero {
        background-color: $bizarre-color;
        padding-top: 115px;
        padding-bottom: 122px;


        h3 {
            text-transform: uppercase;
            font-size: 12px;
            text-align: center;
            font-weight: bold;
            letter-spacing: 5px;
            padding-bottom: 25px;
            color: $nevada-color;
        }

        p {
            text-align: center;
            font-size: 26px;
            letter-spacing: 2%;
            color: $nevada-color;
        }
    }
}
</style>




