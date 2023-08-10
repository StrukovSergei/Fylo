<template>
  <section class="container home text-center">
    <img src="../assets/illustration-intro.png" alt="">
    <h1 class="title text-center">
      All your files in one secure location,
    </h1>
    <h1 class="title text-center">
      accessible anywhere.
    </h1>
    <p class="description text-center">
      Fylo stores all your most important files in one secure location.
      Access them wherever you need, share and collaborate with
      friends family, and co-workers.
    </p>
    <button class="start-btn">Get Started</button>

    <UserCards></UserCards>
    <Hero></Hero>
    <ReviewList></ReviewList>

    <div class="early-access-box">
      <h1 class="early-access-title">Get early access today</h1>
      <p class="early-access-text">It only takes a minute to sign up and our free starter tier is extremely generous. If
        you have any questions, our support team would be happy to help you.
      </p>
      <div class="early-access-input">
        <input type="text" placeholder="email@example.com">
        <button>Get Started For Free</button>
      </div>
    </div>

  </section>
</template>

<script>
import UserCards from '../cmps/UserCards.vue'
import Hero from '../cmps/Hero.vue'
import ReviewList from '../cmps/ReviewList.vue'
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
    UserCards,
    Hero,
    ReviewList
  }

}
</script>
