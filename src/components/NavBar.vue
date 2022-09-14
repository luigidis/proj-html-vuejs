<template>
    <div class="bg-nav">
        <nav class="nav-wrapper container py-2">
            <div class="nav-logo">
                <img src="../assets/img/logo.png" alt="Logo Avada Forum">
            </div>
            <ul class="nav-list-wrapper">
                <li class="nav-item">Home</li>
                <li class="nav-item">Apple</li>
                <li class="nav-item">Microsoft</li>
                <li class="nav-item">Android</li>
                <li class="nav-item">Forums</li>
                <li class="nav-item">Contact us</li>
                <li class="nav-item">
                    <a href="#">Join Us</a>
                </li>
                <li class="nav-item">
                    Search
                </li>
            </ul>
        </nav>
    </div>
</template>

<script>
export default {
    name: 'NavBar'
}
</script>

<style lang="scss" scoped>
@import '../styles/variables.scss';

* {
    

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
                gap: 30px;
            }
                
        }
    }

}

</style>