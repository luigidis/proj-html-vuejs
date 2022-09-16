<template>
    <div class="forum_section">
        <div class="container">
            <div class="title_forums">
                <h3>Phasellus Eget Metus</h3>
                <h2>Forum Sections</h2>
            </div>
            <div class="forums_container">
                <div class="forum_item">
                    <div class="icon_container">
                        <font-awesome-icon icon="fa-solid fa-file-lines" ></font-awesome-icon>
                    </div>
                    <h4>News & Community</h4>
                </div>
                <div class="forum_item">
                    <div class="icon_container">
                        <font-awesome-icon icon="fa-brands fa-apple" ></font-awesome-icon>
                    </div>
                    <h4>Apple Forum</h4>
                </div>
                <div class="forum_item">
                    <div class="icon_container">
                        <font-awesome-icon icon="fa-brands fa-windows" ></font-awesome-icon>
                    </div>
                    <h4>Microsoft Forum</h4>
                </div>
                <div class="forum_item">
                    <div class="icon_container">
                        <font-awesome-icon icon="fa-brands fa-android" ></font-awesome-icon>
                    </div>
                    <h4>Android Forum</h4>
                </div>
                <div class="forum_item">
                    <div class="icon_container">
                        <font-awesome-icon icon="fa-solid fa-mug-saucer" ></font-awesome-icon>
                    </div>
                    <h4>General Discussion</h4>
                </div>
                <div class="forum_item">
                    <div class="icon_container">
                        <font-awesome-icon icon="fa-solid fa-cubes" ></font-awesome-icon>
                    </div>
                    <h4>Apps & Software</h4>
                </div>
                <div class="forum_item">
                    <div class="icon_container">
                        <font-awesome-icon icon="fa-solid fa-laptop"></font-awesome-icon>
                    </div>
                    <h4>Gadget & Stuff</h4>
                </div>
                <div class="forum_item">
                    <div class="icon_container">
                        <font-awesome-icon icon="fa-solid fa-wrench"></font-awesome-icon>
                    </div>
                    <h4>Tutorial & Guides</h4>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'ForumSection'
}
</script>

<style lang="scss" scoped>
@import '../styles/variables.scss';

.forum_section {
    background-color: $bizarre-color;
    .title_forums {
        position: relative;
        margin-bottom: 45px;
        padding-top: 115px;

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

    .title_forums::after {
        content: "";
        width: 80px;
        height: 3px;
        background-color: salmon;
        position: absolute;
        bottom: 0;
        left: 50%;
        transform: translate(-50%, -50%)
    }

    .forums_container {
        display: grid;
        grid-template-columns: repeat(4, 1fr);
        gap: 45px;
        justify-items: center;
        padding-bottom: 54px;

        .forum_item {
            display: flex;
            justify-content: center;
            flex-direction: column;
            align-items: center;
            background-color: white;
            border-top: solid $bostonBlue;
            padding: 45px 35px;
            width: 240px;


            .icon_container {
                border-radius: 50px;
                background-color: salmon;
                text-align: center;
                width: 80px;
                height: 80px;
                display: flex;
                justify-content: center;
                align-items: center;
                color: white;
                font-size: 30px;
                margin-bottom: 20px;
            }

            h4 {
                font-size: 16px;
                font-weight: bold;

            }
        }
    }
}
</style>
        
        