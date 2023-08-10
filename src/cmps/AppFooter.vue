<template>
    <footer>

            <span class="logo">
                <img class="small-svg" src="../assets/Fill_1.png" alt="">
                <img class="small-logo" src="../assets/Fill_2.png" alt="">
            </span>

        <div>
            <div class="footer-text">
                <span v-html="$svg('location')"></span>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et
                dolore
                magna aliqua
            </div>
            <div class="footer-contact">
                <span v-html="$svg('phone')"></span>
                <p class="number">+1-543-123-4567</p>
                <span v-html="$svg('mail')"></span>
                <p class="mail">example@fylo.com</p>
            </div>
            <nav class="footer-links1">
                <RouterLink to="">About Us</RouterLink>
                <RouterLink to="">Jobs</RouterLink>
                <RouterLink to="">Press</RouterLink>
                <RouterLink to="">Blog</RouterLink>
            </nav>
            <nav class="footer-links2">
                <RouterLink to="">Contact Us</RouterLink>
                <RouterLink to="">Terms</RouterLink>
                <RouterLink to="">Privacy</RouterLink>
            </nav>
            <div class="icons">
                <img src="../assets/icons.png" alt="">
            </div>
        </div>
    </footer>
</template>
<script>
export default {
    computed: {

    }
}
</script>