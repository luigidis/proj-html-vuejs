<template>
    <div class="card_triple">
        <!-- <div class="card_mine d-flex flex-column" v-for="poster in posters" :key="poster.id">
            <figure class="img_container">
                <img :src="`${poster.src}`" alt="">
            </figure>
            <div class="text_container">
                <h4>{{ poster.h4 }}</h4>
                <p class="date">{{ poster.date}} </p>
                <p class="content">
                    {{ poster.content }}
                </p>
            </div>
        </div> -->
        <div class="card_mine d-flex flex-column">
            <figure class="img_container">
                <img src="../assets/img/post_feat_img_22-320x202.jpg" alt="">
            </figure>
            <div class="text_container">
                <h4>Fusce sollicitudin nunc sed placerat varius</h4>
                <p class="date">October 11th, 2015 | Comments Off </p>
                <p class="content">
                    Donec finibus sit amet arci eget ultricies. Praesent posuere ante ut erat fringilla, vestibulum
                    placerat metus mattis. Aenean dictum vitae nisl.
                </p>
            </div>
        </div>
        <div class="card_mine d-flex flex-column">
            <figure class="img_container">
                <img src="../assets/img/post_feat_img_21-320x202.jpg" alt="">
            </figure>
            <div class="text_container">
                <h4>Donec facilis sodales leo sit amet leoreet</h4>
                <p class="date">October 11th, 2015 | Comments Off </p>
                <p class="content">
                    Donec finibus sit amet arci eget ultricies. Praesent posuere ante ut erat fringilla, vestibulum
                    placerat metus mattis. Aenean dictum vitae nisl.
                </p>
            </div>
        </div>
        <div class="card_mine d-flex flex-column">
            <figure class="img_container">
                <img src="../assets/img/post_feat_img_20-320x202.jpg" alt="">
            </figure>
            <div class="text_container">
                <h4>Proin eu purus sed aru aliquet curabir vens</h4>
                <p class="date">October 11th, 2015 | Comments Off </p>
                <p class="content">
                    Donec finibus sit amet arci eget ultricies. Praesent posuere ante ut erat fringilla, vestibulum
                    placerat metus mattis. Aenean dictum vitae nisl.
                </p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'TripleCards',
    props: {
        
    },
    // data() {
    //     return {
    //         posters: [
    //             {
    //                 src: '../assets/img/post_feat_img_25-320x202.jpg',
    //                 h4: 'Morbi vitae dui euismod vulputate sollicitudin',
    //                 date: 'October 11th, 2015 | 2 Comments',
    //                 content: 'Donec finibus sit amet arci eget ultricies. Praesent posuere ante ut erat fringilla, vestibulum  placerat metus mattis. Aenean dictum vitae nisl.',
    //                 id: 1
    //             },
    //             {
    //                 src: '../assets/img/post_feat_img_24-320x202.jpg',
    //                 h4: 'Morbi vitae dui euismod vulputate sollicitudin',
    //                 date: 'October 11th, 2015 | 2 Comments',
    //                 content: 'Donec finibus sit amet arci eget ultricies. Praesent posuere ante ut erat fringilla, vestibulum  placerat metus mattis. Aenean dictum vitae nisl.',
    //                 id: 2
    //             },
    //             {
    //                 src: '../assets/img/post_feat_img_23-320x202.jpg',
    //                 h4: 'Morbi vitae dui euismod vulputate sollicitudin',
    //                 date: 'October 11th, 2015 | 2 Comments',
    //                 content: 'Donec finibus sit amet arci eget ultricies. Praesent posuere ante ut erat fringilla, vestibulum  placerat metus mattis. Aenean dictum vitae nisl.',
    //                 id: 3
    //             }
    //         ]
    //     }

    // }



}
</script>

<style lang="scss" scoped>
.card_triple {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 30px;

    .card_mine {
        

        .img_container {
            max-width: 370px;
            img {
                width: 100%;
            }
        }

        .text_container {
            h4 {
                font-size: 15px;
                font-weight: bold;

            }

            .date {
                font-size: 12px;
            }

            .content {
                font-size: 14px;
            }
        }
    }

}
</style>