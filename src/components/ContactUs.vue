<template>
    <div>
        <div class="container footer_contacts">
            <div class="copyright">
                &copy; Copyright 2012-2020 | Avada Theme by Theme Fusion | All rights Reserved | Powered by WordPress
            </div>

            <ul class="icon_container">
                <li class="icon_wrapper bg_facebook">
                    <a href="">
                        <font-awesome-icon icon="fa-brands fa-facebook-f"></font-awesome-icon>
                    </a>
                </li>
                <li class="icon_wrapper bg_twitter">
                    <a href="">
                        <font-awesome-icon icon="fa-brands fa-twitter"></font-awesome-icon>
                    </a>
                </li>
                <li class="icon_wrapper bg_instagram">
                    <a href="">
                        <font-awesome-icon icon="fa-brands fa-instagram"></font-awesome-icon>
                    </a>
                </li>
                <li class="icon_wrapper bg_youtube">
                    <a href="">
                        <font-awesome-icon icon="fa-brands fa-youtube"></font-awesome-icon>
                    </a>
                </li>
            </ul>

        </div>
    </div>
</template>

<script>
export default {
    name: 'ContactUs'
}
</script>

<style lang="scss" scoped>
@import '../styles/variables.scss';

.footer_contacts {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding-top: 50px;
    padding-bottom: 50px;

    .copyright {
        font-size: 12px;
    }

    .icon_container {
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 8px;

        .icon_wrapper {
            font-size: 20px;
            border-radius: 50px;
            color: white;
            width: 45px;
            aspect-ratio: 1;
            text-align: center;
            display: flex;
            justify-content: center;
            align-items: center;
        }
    }

    .bg_youtube {
        background-color: $totemPole-color;
    }

    .bg_twitter {
        background-color: $bostonBlue;
    }

    .bg_facebook {
        background-color: $sanMarino-color;
    }

    .bg_instagram {
        background-color: $wedgewood-color;
    }
}
</style>