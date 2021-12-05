<template>
  <Navbar></Navbar>
  <BigRedComicContainer></BigRedComicContainer>
  <GoalsContainer></GoalsContainer>
  <FaqContainer></FaqContainer>
  <BottomContainer></BottomContainer>
</template>

<script>
import Navbar from './Navbar.vue'
import BigRedComicContainer from './BigRedComicContainer.vue';
import GoalsContainer from './GoalsContainer.vue';
import FaqContainer from './FaqContainer.vue';
import BottomContainer from './BottomContainer.vue';

export default {
  name: 'LandingPage',
  components: {
    Navbar,
    BigRedComicContainer,
    GoalsContainer,
    FaqContainer,
    BottomContainer
  }
}
</script>
