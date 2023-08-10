<template>
    <section class="card-container text-center">
        <div class="first-card">
            <span class="computer-svg" v-html="$svg('computer')"></span>
            <h1 class="card-title text-center">
                Access your files, anywhere
            </h1>

            <p class="card-description text-center">
                The ability to use a smartphone, tablet, or computer to access your account means your files follow you everywhere.
            </p>
        </div>
        <div class="second-card">
            <span class="computer-svg" v-html="$svg('shield')"></span>
            <h1 class="card-title text-center">
                Security you can trust
            </h1>

            <p class="card-description text-center">
                2-factor authentication and user-controlled encryption are just a couple of the security features we allow to help secure your files.
            </p>
        </div>
        <div class="third-card">
            <span class="computer-svg" v-html="$svg('collab')"></span>
            <h1 class="card-title text-center">
                Real-time collaboration
            </h1>

            <p class="card-description text-center">
                Securely share files and folders with friends, family and colleagues for live collaboration. No email attachments required.
            </p>
        </div>
        <div class="forth-card">
            <span class="computer-svg" v-html="$svg('folder')"></span>
            <h1 class="card-title text-center">
                Store any type of file
            </h1>

            <p class="card-description text-center">
                Whether you're sharing holidays photos or work documents, Fylo has you covered allowing for all file types to be securely stored and shared.
            </p>
        </div>
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
  