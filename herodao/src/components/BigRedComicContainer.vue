<template>
  <div
      class="md:overflow-hidden sm:overflow-hidden bg-herodao-red bg-blend-soft-light bg-moonship-art bg-cover bg-no-repeat sm:h-108 h-80">
    <div
        class="absolute text-left top-28 left-6 sm:top-48 sm:left-20 sm:text-4xl font-bold font-architects-daughter text-white">
      A DAO to reboot <br> comic book heroes <br> who have fallen into <br> the public domain
    </div>
    <a @click="setShow" href="https://discord.gg/YeZjTvdWBt">
      <img v-if="!active" class="absolute hover:shadow-xl h-6 top-56 left-6 sm:h-14 sm:top-96 sm:left-20"
           src="@/assets/joinourdiscord.svg">
    </a>
      <img v-if="active" class="absolute bg-transparent h-6 top-56 left-6 sm:h-14 sm:top-96 sm:left-19"
           src="@/assets/joinourdiscordnoshadow.png">
    <div class="flex pointer-events-none justify-right">
      <div class="pl-44 md:pl-132 sm:pl-108 z-50 opacity-100">
        <img src="@/assets/letsbuildacomic.png">
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: "BigRedComicContainer",
  data() {
    return {
      active: false,
      show: false
    };
  },
  methods: {
    setShow() {
      this.active = true;
      setTimeout(() => {
        this.show = true;
      }, 6000);
    }
  }
}
</script>
