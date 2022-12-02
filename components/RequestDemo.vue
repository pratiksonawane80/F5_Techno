<template>
  <div class="">
    <div v-if="windowWidth > 1500" class="flex">
      <div class="m-16">
        <p class="business-text font-normal not-italic">
          LOOK AFTER THE PEOPLE, <br />
          WHO LOOK AFTER YOUR BUSINESS.
        </p>
        <p class="health-text mt-20 font-semibold not-italic">
          HEALTH WELLNESS.
        </p>
        <Button class="mt-8" />
      </div>
      <img
        class="businessman-img justify-end"
        src="../assets/images/businessman-his-office-zen-position 1.png"
        alt=""
      />
    </div>

    <!-- Mobile -->
    <div v-else class="flex flex-col">
      <div >
        <img
		style="width:100%"
          class="businessman-img justify-end"
          src="../assets/images/businessman-his-office-zen-position 1-cropped.png"
          alt=""
        />
      </div>
      <div class="m-10 text-center">
        <p class="business-text font-normal not-italic">
          LOOK AFTER THE PEOPLE, <br />
          WHO LOOK AFTER YOUR BUSINESS.
        </p>
        <p class="health-text mt-20 font-semibold not-italic">
          HEALTH WELLNESS.
        </p>
        <Button class="mt-8" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      windowWidth: 1200,
    }
  },

  beforeMount() {
    this.windowWidth = document.documentElement.clientWidth
  },
}
</script>

<style scoped>
.main-div {
  height: 600px;
  background-repeat: no-repeat;
}

.businessman-img {
  height: 501px;
}

.business-text {
  font-size: 28px;
  line-height: 151.02%;
}

.health-text {
  font-size: 28px;
  line-height: 34px;
}

.content-wrapper {
  background-image: url('../assets/images/businessman-his-office-zen-position 1.png');
}
</style>
