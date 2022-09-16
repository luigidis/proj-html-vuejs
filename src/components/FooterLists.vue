<template>
    <div>
        <div class="container">
            <div class="lists_wrapper">
                <ul class="col-3">
                    <li id="item_none">
                        <h6>Avada Tech Forum</h6>
                    </li>
                    <li id="item_none" class="text_color_silver">
                        Sed semper, nisl id feugiat eleifend, erat est digssim felis, quis auctor elit enim nec ante,
                        Cras et nibh risus.
                        Pelientesque non mi sit amet mi intermentum.
                    </li>
                </ul>
                <ul class="col-3">
                    <li id="item_none">
                        <h6>Popular Topics</h6>
                    </li>
                    <li>
                        <div class="pe-1">
                            <font-awesome-icon icon="fa-solid fa-angle-right"></font-awesome-icon>
                        </div>
                        Nam a dolor voluptat massa auctor semper
                    </li>
                    <li>
                        <div class="pe-1">
                            <font-awesome-icon icon="fa-solid fa-angle-right"></font-awesome-icon>
                        </div>
                        Sed euismod nuinc urna fermentum arcu dapibus fringilla.
                    </li>
                    <li>
                        <div class="pe-1">
                            <font-awesome-icon icon="fa-solid fa-angle-right"></font-awesome-icon>
                        </div>
                        Cras lacinia tellus id mauris finibus lacus molestie
                    </li>
                    <li>
                        <div class="pe-1">
                            <font-awesome-icon icon="fa-solid fa-angle-right"></font-awesome-icon>
                        </div>
                        Curabitur a scelerisque ligula
                    </li>
                </ul>
                <ul class="col-3">
                    <li id="item_none">
                        <h6>Recent Topics</h6>
                    </li>
                    <li>
                        <div class="pe-1">
                            <font-awesome-icon icon="fa-solid fa-angle-right"></font-awesome-icon>
                        </div>
                        Cras lacinia tellus id mauris finibus lacus molestie
                    </li>
                    <li>
                        <div class="pe-1">
                            <font-awesome-icon icon="fa-solid fa-angle-right"></font-awesome-icon>
                        </div>
                        Proin at ligula sagittis vestibulum nisi vitae
                    </li>
                    <li>
                        <div class="pe-1">
                            <font-awesome-icon icon="fa-solid fa-angle-right"></font-awesome-icon>
                        </div>
                        Sed nec metus at est tincidunt elementum
                    </li>
                    <li>
                        <div class="pe-1">
                            <font-awesome-icon icon="fa-solid fa-angle-right"></font-awesome-icon>
                        </div>

                        Nella egestas nulla eu nulla suscipit molestie
                    </li>
                </ul>
                <ul class="col-3">
                    <li id="item_none">
                        <h6>Latest Replies</h6>
                    </li>
                    <li>
                        <div class="pe-1">
                            <font-awesome-icon icon="fa-solid fa-angle-right"></font-awesome-icon>
                        </div>
                        Cras lacinia tellus id mauris finibus lacus molestie
                    </li>
                    <li>
                        <div class="pe-1">
                            <font-awesome-icon icon="fa-solid fa-angle-right"></font-awesome-icon>
                        </div>
                        Cras lacinia tellus id mauris finibus lacus molestie
                    </li>
                    <li>
                        <div class="pe-1">
                            <font-awesome-icon icon="fa-solid fa-angle-right"></font-awesome-icon>
                        </div>
                        Nella egestas nulla eu nulla suscipit molestie
                    </li>
                    <li class="d-flex">
                        <div class="pe-1">
                            <font-awesome-icon icon="fa-solid fa-angle-right"></font-awesome-icon>
                        </div>
                        <p>Mauris ac nibh quis eros sagittis lacinia a et dui</p>
                    </li>

                </ul>
            </div>



        </div>
    </div>
</template>

<script>
export default {
    name: 'FooterList'
}
</script>

<style lang="scss" scoped>
@import '../styles/variables.scss';

.container {
    padding-top: 75px;
    padding-bottom: 65px;

    .lists_wrapper {
        display: flex;
        gap: 25px;

        ul {
            li {
                display: flex;
                font-size: 12px;
                font-weight: bold;
                border-bottom: solid 1px rgba(128, 128, 128, 0.148);
                padding-bottom: 20px;
                padding-top: 15px;

                h6 {
                    font-size: 16px;
                    font-weight: bold;
                    text-transform: uppercase;
                    color: $shark-color;
                    padding-top: 0px;
                }
            }

            #item_none {
                border-bottom: none;
            }

            .text_color_silver {
                color: $silverChalice-color;
            }
        }
    }
}
</style>