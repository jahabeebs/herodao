<template>
  <div class="bg-green-100 sm:h-112 h-80">
    <div class="flex flex-row justify-evenly">
    <div class="flex flex-col sm:pt-24 pt-8 sm:space-y-4 space-y-2">
      <div class="flex justify-center">
        <img class="flex sm:h-28 h-12" src="@/assets/poolfunds.svg">
      </div>
      <div class="flex font-architects-daughter justify-center font-extrabold sm:text-2xl">Pool funds</div>
      <div class="flex font-avenir justify-center sm:text-2xl text-xs">1 share = $1 = 1 wxDai</div>
      <div class="flex flex-col sm:space-y-4 space-y-2 sm:pt-8">
        <img class="flex sm:h-28 h-12" src="@/assets/create.svg">
        <div class="flex font-architects-daughter justify-center font-extrabold sm:text-2xl">Create</div>
        <div class="flex font-avenir justify-center sm:text-2xl text-xs">Use pooled funds to illustrate and write an original work</div>
      </div>
    </div>
    <div class="flex flex-col sm:space-y-4 space-y-2 justify-center">
      <div class="flex font-aAhaWow sm:text-4xl sm:pt-8 text-lg justify-center">Goals</div>
      <div class="flex justify-center">
        <img class="flex sm:h-28 h-12" src="@/assets/pickhero.svg">
      </div>
      <div class="flex font-architects-daughter justify-center font-extrabold sm:text-2xl">Pick Hero</div>
      <div class="flex font-avenir justify-center sm:text-2xl text-xs">From the public domain</div>
      <div class="flex flex-col sm:space-y-4 space-y-2 sm:pt-8">
        <img class="flex sm:h-28 h-12" src="@/assets/print.svg">
        <div class="flex font-architects-daughter justify-center font-extrabold sm:text-2xl">Print</div>
        <div class="flex font-avenir justify-center sm:text-2xl text-xs">Print physical copies for DAO members + sales</div>
      </div>
    </div>
      <div class="flex flex-col sm:pt-24 pt-8 sm:space-y-4 space-y-2">
        <div class="flex justify-center">
          <img class="flex sm:h-28 h-12" src="@/assets/reboot.svg">
        </div>
        <div class="flex font-architects-daughter justify-center font-extrabold sm:text-2xl">Reboot</div>
        <div class="flex font-avenir justify-center sm:text-2xl text-xs">Vote on how to give new life to a hero</div>
        <div class="flex flex-col sm:space-y-4 space-y-2 sm:pt-8">
          <img class="flex sm:h-28 h-12" src="@/assets/distribute.svg">
          <div class="flex font-architects-daughter justify-center font-extrabold sm:text-2xl">Distribute</div>
          <div class="flex font-avenir justify-center sm:text-2xl text-xs">DAO members get comics, and profits go back to the DAO</div>
        </div>
      </div>
    </div>
  </div>
</template>


<script>

export default {
  name: "GoalsContainer",
}
</script>