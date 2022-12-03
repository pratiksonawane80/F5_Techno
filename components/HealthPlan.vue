<template>
  <div main-div>
    <div class="lg:flex flex-auto relative lg:max-h-full" :class="[imagePosition ? 'flex-row-reverse' : '']">
      <div class="w-screen heal w-1/2" :style="{ backgroundColor: activeColor}">
        <div class="p-20">
          <div class="font-bold heal-text mb-5" :style="{ color: color}">{{ header }}</div>
          <div>
            <ul class="list-disc text-white" :style="{ color: color}">
              <li class="mb-5">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.<br />
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              </li>
              <li class="mb-5">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.<br />
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              </li>
              <li class="mb-5">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.<br />
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              </li>
            </ul>
          </div>
        </div>
      </div>

      <div>
        <img
          class="
            absolute
            center-img
            lg:top-1/2
            left-1/2
            transform
            -translate-x-1/2 -translate-y-1/2
          "
          src="../assets/images/alternative-medicine@2x 1.png"
          alt="hero-img"
        />
      </div>

      <div class="w-screen bg-cover w-1/2 lg:h-full h-48">
        <img class="h-full w-full object-cover" :src="image" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HealthPlan',
  props: ['image', 'header', 'activeColor', 'color', 'imagePosition'], // eslint-disable-line vue/require-prop-types
  data() {
    return {
	}
  },
}
</script>

<style scoped>
.heal {
  background-color: #284948;
  height: auto;
}

.engage {
  background-color: #fbfee9;
  height: 397px;
}

.health-text {
  font-size: 26px;
}

.heal-text {
  font-style: normal;
  font-weight: 700;
  font-size: 26px;
  line-height: 31px;
  color: #c3d797;
}

.engage-text {
  font-style: normal;
  font-weight: 700;
  font-size: 26px;
  line-height: 31px;
}

.engage-list {
  color: #2c2c2c;
}

.center-img {
  background-color: #fff;
  padding: 12px;
  border-radius: 50%;
}
</style>
