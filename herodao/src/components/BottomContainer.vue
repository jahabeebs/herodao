<template>
  <div class="flex bg-herodao-gold justify-center h-auto overflow-hidden">
    <div class="flex flex-row space-x-2 md:space-x-16 sm:space-x-28">
      <div class="mb-2 sm:ml-56 md:ml-16 ml-4 mt-4 md:mt-4 sm:mt-10 space-y-1">
        <div class="flex flex-row space-x-2">
          <img class="flex h-8 md:h-12 sm:h-16" src="@/assets/herodaologo.svg">
          <img class="flex h-3 mt-3 md:mt-3 md:h-6 sm:h-6 sm:mt-5" src="@/assets/herodaoname.svg">
        </div>
        <div class="font-avenir pr-1 text-xxs md:text-sm sm:text-lg text-left text-black font-bold">The world's first
          and
          largest DAO <br> centered around launching a
          real <br>
          physical comic book and hero <br> franchise owned by its fans.
        </div>
        <div>
          <a @click="setShow" href="https://discord.gg/YeZjTvdWBt">
            <img v-if="!active" class="h-6 sm:h-8 hover:shadow-lg" src="@/assets/joinourdiscord.svg">
            <img v-if="active" class="h-6 sm:h-8 hover:shadow-lg" src="@/assets/joinourdiscordnoshadow.png">
          </a>
        </div>
      </div>
      <div class="flex flex-col pr-1 text-xxs sm:text-sm mt-2 md:mt-6 sm:mt-4">
        <div class="flex font-bold hover:underline">Lorem Ipsum</div>
        <div class="hover:underline">Lorem Ipsum</div>
        <div class="hover:underline">Lorem Ipsum</div>
        <div class="hover:underline">Lorem Ipsum</div>
        <div class="hover:underline">Lorem Ipsum</div>
        <div class="hover:underline">Lorem Ipsum</div>
        <div class="hover:underline">Lorem Ipsum</div>
        <div class="hover:underline">Lorem Ipsum</div>
        <div class="hover:underline">Lorem Ipsum</div>
        <div class="hover:underline">Lorem Ipsum</div>
      </div>
      <div class="flex flex-col flex-shrink text-xxs mt-2 mb-2 sm:text-sm md:mt-6 sm:mt-4">
        <div class="flex font-bold hover:underline">Lorem Ipsum</div>
        <div class="hover:underline">Lorem Ipsum</div>
        <div class="hover:underline">Lorem Ipsum</div>
        <div class="hover:underline">Lorem Ipsum</div>
        <div class="hover:underline">Lorem Ipsum</div>
        <div class="hover:underline">Lorem Ipsum</div>
        <div class="hover:underline">Lorem Ipsum</div>
        <div class="hover:underline">Lorem Ipsum</div>
        <div class="hover:underline">Lorem Ipsum</div>
        <div class="hover:underline">Lorem Ipsum</div>
      </div>
      <div class="flex flex-col flex-shrink text-xxs pl-1 mt-2 sm:text-sm md:mt-6 sm:mt-4">
        <div class="flex font-bold hover:underline">Lorem Ipsum</div>
        <div class="hover:underline">Lorem Ipsum</div>
        <div class="hover:underline">Lorem Ipsum</div>
        <div class="hover:underline">Lorem Ipsum</div>
        <div class="hover:underline">Lorem Ipsum</div>
        <div class="hover:underline">Lorem Ipsum</div>
        <div class="hover:underline">Lorem Ipsum</div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: "BottomContainer",
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
