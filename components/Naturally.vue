<template>
  <div class="main-div bg-no-repeat bg-cover pt-32 pb-32">
    <div class="float-left py-24 px-10 text-center">
      <img src="../assets/images/Line 1.png" alt="horizontal-line" />
      <div class="font-bold text-4xl pt-10">WE HEAL YOU</div>
      <div class="font-medium text-xl naturally pt-10">NATURALLY</div>
      <img
        class="pt-10"
        src="../assets/images/Line 1.png"
        alt="horizontal-line"
      />
    </div>

    <div class="flex flex-row flex-wrap justify-around">
      <div>
        <div class="square">
          <img
            class="image"
            src="../assets/images/homeopathy-2@2x 1.png"
            alt="green-shaded-background"
          />
        </div>
        <p class="text-center font-medium text-lg pt-4">Ayurveda</p>
      </div>
      <div>
        <div class="square">
          <img
            class="image"
            src="../assets/images/pills 3.png"
            alt="green-shaded-background"
          />
        </div>
        <p class="text-center font-medium text-lg pt-4">Homeopathy</p>
      </div>
      <div>
        <div class="square">
          <img
            class="image"
            src="../assets/images/homeopathy-2@2x 1.png"
            alt="green-shaded-background"
          />
        </div>
        <p class="text-center font-medium text-lg pt-4">Naturopathy</p>
      </div>
      <div>
        <div class="square">
          <img
            class="image"
            src="../assets/images/pills 3.png"
            alt="green-shaded-background"
          />
        </div>
        <p class="text-center font-medium text-lg pt-4">Yoga</p>
      </div>
    </div>

    <div class="flex flex-row justify-around mt-10">
      <div>
        <div class="square">
          <img
            class="image"
            src="../assets/images/homeopathy-2@2x 1.png"
            alt="green-shaded-background"
          />
        </div>
        <p class="text-center font-medium text-lg pt-4">Meditation</p>
      </div>
      <div>
        <div class="square">
          <img
            class="image"
            src="../assets/images/pills 3.png"
            alt="green-shaded-background"
          />
        </div>
        <p class="text-center font-medium text-lg pt-4">Physiotherapy</p>
      </div>
      <div>
        <div class="square">
          <img
            class="image"
            src="../assets/images//homeopathy-2@2x 1.png"
            alt="green-shaded-background"
          />
        </div>
        <p class="text-center font-medium text-lg pt-4">Nutrition</p>
      </div>
      <div>
        <div class="square">
          <img
            class="image"
            src="../assets/images/homeopathy-2@2x 1.png"
            alt="green-shaded-background"
          />
        </div>
        <p class="text-center font-medium text-lg pt-4">Psychology</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HealNaturally',
}
</script>

<style scoped>
.main-div {
  background-image: url('../assets/images/5333978 1.png');
}

.naturally {
  font-size: 44px;
}

.green-rect {
  background: linear-gradient(180deg, #284948 0%, #3e8c58 100%);
  border-radius: 5px;
  padding: 33.25;
}

.square {
  width: 133px;
  height: 133px;
  background: linear-gradient(180deg, #284948 0%, #3e8c58 100%);
  position: relative;
  border-radius: 5px;
}

.image {
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
}
</style>
