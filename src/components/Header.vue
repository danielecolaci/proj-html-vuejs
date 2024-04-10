<script>
export default {
    name: 'Header',
    data() {
        return {
            modal: false
        }
    },
    methods: {
        modalOpen() {
            this.modal = !this.modal
        },
        modalClose() {
            this.modal = false
        }
    }
}
</script>

<template>
    <div class="modale flex column flex-center" v-if="modal">
        <h3 class="current">Home</h3>
        <h3>About Us</h3>
        <h3>Services</h3>
        <h3>Shop</h3>
        <h3>Our Team</h3>
        <h3>Blog</h3>
        <h3>Contact Us</h3>
        <i class="fa-solid fa-xmark" @click="modalClose"></i>
    </div>

    <header id="header">
        <div class="container">
            <nav class="flex">
                <div class="logo image"></div>
                <div class="icon flex">
                    <i class="fa-solid fa-cart-shopping"></i>
                    <i class="fa-solid fa-bars" @click="modalOpen"></i>
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