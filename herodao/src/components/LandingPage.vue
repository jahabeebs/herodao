<template>
  <Navbar></Navbar>
  <BigRedComicContainer></BigRedComicContainer>
  <GoalsContainer></GoalsContainer>
</template>

<script>
import Navbar from './Navbar.vue'
import BigRedComicContainer from './BigRedComicContainer.vue';
import GoalsContainer from './GoalsContainer.vue';

export default {
  name: 'LandingPage',
  components: {
    Navbar,
    BigRedComicContainer,
    GoalsContainer
  }
}
</script>
