<template>
  <header>
    <span class="logo">
      <img class="small-svg" src="../assets/Fill_1.png" alt="">
      <img class="small-logo" src="../assets/Fill_2.png" alt="">
    </span>
    <nav class="links">
      <RouterLink to="">Features</RouterLink>
      <RouterLink to="">Team</RouterLink>
      <RouterLink to="">Sign in</RouterLink>
    </nav>
    <section class="loggedin-user" v-if="loggedInUser">
      <RouterLink :to="`/user/${loggedInUser._id}`">
        {{ loggedInUser.fullname }}
      </RouterLink>
      <span>{{ loggedInUser.score?.toLocaleString() }}</span>
      <img :src="loggedInUser.imgUrl" />
    </section>
  </header>
</template>
<script>
export default {
  computed: {
    loggedInUser() {
      return this.$store.getters.loggedinUser
    },
  }
}
</script>