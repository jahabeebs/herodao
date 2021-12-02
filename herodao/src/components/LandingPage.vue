<template>
  <div>
  <Navbar></Navbar>
  </div>
  <BigRedComicContainer></BigRedComicContainer>
</template>

<script>
import Navbar from './Navbar.vue'
import BigRedComicContainer from './BigRedComicContainer.vue';

export default {
  name: 'LandingPage',
  components: {
    Navbar,
    BigRedComicContainer
  }
}
</script>
