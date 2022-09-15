<template>
    <div class="bg-nav">
        <nav class="nav-wrapper container py-2">
            <div class="nav-logo">
                <img src="../assets/img/logo.png" alt="Logo Avada Forum">
            </div>
            <ul 
                class="nav-list-wrapper"
                v-for="item in navBarItems"
                :key="item.id">
                <li 
                    class="nav-item"
                    :id="item.item_id">
                    <a :href="item.link">
                        {{item.item}}
                    </a>
                </li>
                <!-- <li class="nav-item">
                    <a href="#">
                        Apple
                    </a>
                </li>
                <li class="nav-item">
                    <a href="#">
                        Microsoft
                    </a>
                </li>
                <li class="nav-item">
                    <a href="#">
                        Android
                    </a>
                </li>
                <li class="nav-item">
                    <a href="#">
                        Forums
                    </a>
                </li>
                <li class="nav-item">
                    <a href="#">
                        Contact us
                    </a>
                </li>
                <li class="nav-item" id="button_black">
                    <a href="#">
                        Join us
                    </a>
                </li>
                <li class="nav-item">
                    <a href="#">
                        <font-awesome-icon icon="fa-solid fa-magnifying-glass" />
                    </a>
                </li> -->
            </ul>
        </nav>
    </div>
</template>


<script>


export default {
    name: 'NavBar',
    data() {
        return {
            navBarItems: [
                {
                    item: 'Home',
                    link:   '#',
                    item_id: '',
                    id: 1,
                },
                {
                    item: 'Apple',
                    link:   '#',
                    item_id: '',
                    id: 2,
                },
                {
                    item: 'Microsoft',
                    link:   '#',
                    item_id: '',
                    id: 3,
                },
                {
                    item: 'Android',
                    link:   '#',
                    item_id: '',
                    id: 4,
                },
                {
                    item: 'Forum',
                    link:   '#',
                    item_id: '',
                    id: 5,
                },
                {
                    item: 'Contact Us',
                    link:   '#',
                    item_id: '',
                    id: 6,
                },
                {
                    item: 'Join Us',
                    link:   '#',
                    item_id: 'button_black',
                    id: 7,
                },
                {
                    item: `${<font-awesome-icon icon="fa-solid fa-magnifying-glass" />}`,
                    link: '#',
                    item_id: '',
                    id: 8,
                },
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
@import '../styles/variables.scss';

.bg-nav {
    background-color: $easternBlue-color;
    color: white;
    font-size: 0.813rem;

    .nav-wrapper {
        display: flex;
        justify-content: space-between;
        align-items: center;

        .nav-log {
            max-width: 237px;
        }

        .nav-list-wrapper {
            display: flex;
            align-items: center;
            gap: 30px;

            #button_black {
                padding: 10px 20px;
                background-color: $shark-color;
            }
        }

    }
}
</style>