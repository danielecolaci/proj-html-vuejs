<script>
export default {
    name: 'Footer',
    data() {
        return {

        }
    }
}
</script>

<template>
    <footer>

        <div class="container flex">
            <div class="flex column">
                <div class="footer-image first image"></div>
                <button>Shop our range now</button>
            </div>
            <div class="contacts flex text-center column">
                <div class="logo image"></div>
                <p>Avada Barbers<br>123 New York Street<br>New York City<br>info@yourwebsite.com<br>+1
                    (555)
                    555-1212</p>
                <h4>Follow us</h4>
                <div class="icon flex">
                    <i class="fa-brands fa-facebook-f"></i>
                    <i class="fa-brands fa-twitter"></i>
                    <i class="fa-brands fa-youtube"></i>
                    <i class="fa-brands fa-instagram"></i>
                </div>
            </div>
            <div class="flex column">
                <div class="footer-image second image"></div>
                <button>Shop our range now</button>
            </div>
        </div>

        <div class="copyright">
            <p class="center">&copy; Copyright 2024 | Avada Theme by Daniele Colaci | All Rights Reserved |
                Powered
                by Boolean</p>
        </div>
    </footer>
</template>

<style scoped></style>