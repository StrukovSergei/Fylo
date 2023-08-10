<template>
    <section class="hero-container flex">
        <img src="../assets/illustration-stay-productive.png" alt="">
        <span class="hero-text">
            <h1 class="hero-title">Stay productive,</h1>
            <h1 class="hero-title">wherever you are</h1>
                <p class="hero-desc">Never let location be an issue when accessing your files. Fylo has you covered for all of your file storage needs.</p>
                <p class="hero-desc">Securely share files and folders with friends, family and colleagues for live collaboration. No email attachments required.</p>
                <p class="hero-link">See how Fylo works <span v-html="$svg('arrow')"></span></p>
        </span>
    </section>
</template>
  
<script>
export default {
    name: 'home',
    data() {
        return {
        }
    },
    computed: {
    },
    created() {
    },
    methods: {
    },
    components: {

    }

}
</script>
  