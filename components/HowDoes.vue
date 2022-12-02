<template>
  <div class="main-div relative lg:py-14">
    <div class="font-bold head-text text-center lg:p-10 pt-10">HOW DOES THIS WORK ?</div>

    <!-- step 1 -->
    <div class="lg:flex justify-around">
			<div v-if="windowWidth < 1100" class="lg:mt-60">
          <img  class="m-auto" src="../assets/images/Mask Group 2 1.png" alt="" />
        </div>
      <div class="flex flex-col items-center lg:mt-40 mt-10 text-center">
        <div class="font-semibold step pb-5">Step 1</div>
        <div class="font-semibold text-lg content pb-5">
          Lorem ipsum dolor sit amet, consectetur <br />
          adipiscing elit.
        </div>
        <img src="../assets/images/Line 3.png" alt="horizontal-line" />
        <div class="text-lg content pt-5">
          Lorem ipsum dolor sit amet, consectetur <br />
          adipiscing elit.
        </div>
      </div>

      <div class="flex flex-col items-center text-center">
        <div class="font-semibold step pb-5">Step 2</div>
        <div class="font-semibold text-lg content pb-5">
          Lorem ipsum dolor sit <br />
          amet, consectetur <br />
          adipiscing elit.
        </div>
        <img src="../assets/images/Line 3.png" alt="horizontal-line" />
        <div class="text-lg content pt-5">
          Lorem ipsum dolor sit amet, <br />
          consectetur adipiscing elit.
        </div>
      </div>

      <div class="flex flex-col items-center lg:mt-60 mt-10 text-center">
        <div class="font-semibold step pb-5">Step 3</div>
        <div class="font-semibold text-lg content pb-5">
          Lorem ipsum dolor sit amet, consectetur <br />
          adipiscing elit.
        </div>
        <img src="../assets/images/Line 3.png" alt="horizontal-line" />
        <div class="text-lg content pt-5">
          Lorem ipsum dolor sit amet, consectetur <br />
          adipiscing elit.
        </div>
		<div class="lg:mt-16 mt-6 lg:p-0 p-10">
			<Button />
		</div>
      </div>

	<div v-if="windowWidth > 1100" class="absolute lg:mt-60">
          <img src="../assets/images/image (3).png" alt="" />
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HowDoesItWork',
  data() {
	return {
		windowWidth: 0
	}
  },
  beforeMount() {
	this.windowWidth = document.documentElement.clientWidth
  }
}
</script>

<style scoped>
.main-div {
  height: auto;
  background-color: #f9f9f9;
}

.head-text {
  font-size: 26px;
}

.step {
  font-size: 26px;
  color: #dd7a1d;
}

.content {
  color: #2c2c2c;
}
</style>
