<script>
export default {
    name: 'Header',
    data() {
        return {

        }
    }
}
</script>

<template>
    <header id="header">
        <div class="container">
            <nav class="flex">
                <div class="logo image"></div>
                <div class="icon flex">
                    <i class="fa-solid fa-cart-shopping"></i>
                    <i class="fa-solid fa-bars"></i>
                </div>
            </nav>
            <div class="jumbotron flex image">
                <section>
                    <h1 class="serif">Barber Shop</h1>
                    <hr>
                    <p>The Pinnacle of Male Grooming</p>
                    <button>Learn More</button>
                </section>
                <div class="jumbotron-img image"></div>
            </div>
        </div>
    </header>
    <a href="#header" class="btn-fixed flex flex-center">
        <i class="fa-solid fa-chevron-up"></i>
    </a>
</template>

<style scoped></style>