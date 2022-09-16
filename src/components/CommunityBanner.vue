<template>
    <div>
        <div class="bg_container">
            <div class="container top">
                <h2>Hey! Join to our <br> Community</h2>
                <p>
                    Nulla molestie tortor nec lectus venenatis, sed blandit dui finibus. Curabitur feugiat <br>
                    vulputate purus ipsums dolores ficilitis uns etra.
                </p>
                <div class="button_mine">
                    <a href="#">
                        Sign Up 
                        <font-awesome-icon icon="fa-solid fa-angle-right"></font-awesome-icon>
                    </a>
                </div>
            </div>
        </div>
        <div class="bg_color">
            <div class="container bottom">
                <div class="subscriber_container">
                    <h3> Subscribe to our Newsletter</h3>
                    <div class="input_wrapper">
                        <input type="text" placeholder="Insert your email*" class="ps-3">
                        <button class="send">Send</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'CommunityBanner'
}
</script>

<style lang="scss" scoped>
@import '../styles/variables.scss';

.bg_container {
    background-image: url(../assets/img/join_now_cta_bg.jpg);
    background-position: center;
    background-size: 100% 100%;
    height: 550px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;

    .top {
        color: white;
        display: flex;
        flex-direction: column;
        align-items: center;
        text-align: center;

        h2 {
            font-size: 50px;
            font-weight: bold;
        }

        p {
            font-size: 14px;
            margin-top: 20px;
            margin-bottom: 30px;
        }

        .button_mine {
            padding: 10px 20px;
            text-transform: uppercase;
            font-weight: bold;
            font-size: 18px;
            background-color: $easternBlue-color;
            max-width: 160px;

        }
    }

}

.bg_color {
    background-color: $bizarre-color;
    .bottom {
        display: flex;
        justify-content: center;
        align-items: center;
        padding-top: 95px;
        padding-bottom: 115px;
        text-align: center;

        h3 {
            font-size: 25px;
            font-weight: bold;
            padding-bottom: 40px;
        }

        .input_wrapper {
            height: 53px;
            display: flex;
            justify-content: center;

            input {
                height: 100%;
                margin-right: 30px;
                width: 490px;
            }

            .send {
                height: 100%;
                padding: 20px 90px;
                background-color: $shark-color;
                color: white;
                text-transform: uppercase;
                line-height: 10px;
                font-size: 14px;
                font-weight: bold;
                letter-spacing: 1px;
            }
        }
    }
}
</style>