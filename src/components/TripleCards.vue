<template>
    <div class="card_triple">
        <div class="card_mine">
            <figure class="img_container">
                <img src="https://picsum.photos/id/237/370/265" alt="">
            </figure>
            <div class="text_container">
                <h4>Morbi vitae dui euismod vulputate sollicitudin</h4>
                <p class="date">October 11th, 2015 | 2 Comments </p>
                <p class="content">
                    Donec finibus sit amet arci eget ultricies. Praesent posuere ante ut erat fringilla, vestibulum
                    placerat metus mattis. Aenean dictum vitae nisl.
                </p>
            </div>
        </div>
        <div class="card_mine">
            <figure class="img_container">
                <img src="https://picsum.photos/id/237/370/265" alt="">
            </figure>
            <div class="text_container">
                <h4>Morbi vitae dui euismod vulputate sollicitudin</h4>
                <p class="date">October 11th, 2015 | 2 Comments </p>
                <p class="content">
                    Donec finibus sit amet arci eget ultricies. Praesent posuere ante ut erat fringilla, vestibulum
                    placerat metus mattis. Aenean dictum vitae nisl.
                </p>
            </div>
        </div>
        <div class="card_mine">
            <figure class="img_container">
                <img src="https://picsum.photos/id/237/370/265" alt="">
            </figure>
            <div class="text_container">
                <h4>Morbi vitae dui euismod vulputate sollicitudin</h4>
                <p class="date">October 11th, 2015 | 2 Comments </p>
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
    name: 'TripleCards'
}
</script>

<style lang="scss" scoped>
.card_triple {
    display: grid;
    grid-template-columns: repeat(3, 1fr);

    .card_mine {
        .img_container {
            max-width: 370px;
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