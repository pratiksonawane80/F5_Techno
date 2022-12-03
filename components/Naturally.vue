<template>
  <div
    class="main-div bg-no-repeat bg-cover lg:py-32 py-10 lg:flex lg:justify-around"
  >
    <div class="lg:py-24 py-10 px-10 text-center">
      <img src="../assets/images/Line 1.png" alt="horizontal-line" />
      <p class="font-bold text-4xl pt-10">WE HEAL YOU</p>
      <p class="font-medium text-xl naturally pt-10">NATURALLY</p>
      <img
        class="pt-10"
        src="../assets/images/Line 1.png"
        alt="horizontal-line"
      />
    </div>

    <div class="w-full">
      <div class="lg:flex justify-around">
        <div v-for="data in dataArray1" :key="data.image">
          <div class="square m-auto">
            <img
              class="
                absolute
                top-1/2
                left-1/2
                transform
                -translate-x-1/2 -translate-y-1/2
              "
              :src="data.image"
              alt="green-shaded-background"
            />
          </div>
          <p class="text-center font-medium text-lg lg:pt-4 pb-4">
            {{ data.name }}
          </p>
        </div>
      </div>

      <div class="lg:flex justify-around lg:mt-10">
        <div v-for="data in dataArray2" :key="data.image">
          <div class="square m-auto">
            <img
              class="
                absolute
                top-1/2
                left-1/2
                transform
                -translate-x-1/2 -translate-y-1/2
              "
              :src="data.image"
              alt="green-shaded-background"
            />
          </div>
          <p class="text-center font-medium text-lg lg:pt-4 pb-4">
            {{ data.name }}
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HealNaturally',
  data() {
    return {
      dataArray1: [
        {
          name: 'Ayurveda',
          image: 'https://i.postimg.cc/fLRCQpBZ/homeopathy-2-2x-1.png',
        },
        {
          name: 'Homeopathy',
          image: 'https://i.postimg.cc/c1jmPDYy/pills-3.png',
        },
        {
          name: 'Naturopathy',
          image: 'https://i.postimg.cc/fLRCQpBZ/homeopathy-2-2x-1.png',
        },
        {
          name: 'Yoga',
          image: 'https://i.postimg.cc/c1jmPDYy/pills-3.png',
        },
      ],
      dataArray2: [
        {
          name: 'Meditation',
          image: 'https://i.postimg.cc/fLRCQpBZ/homeopathy-2-2x-1.png',
        },
        {
          name: 'Physiotherapy',
          image: 'https://i.postimg.cc/c1jmPDYy/pills-3.png',
        },
        {
          name: 'Nutrition',
          image: 'https://i.postimg.cc/fLRCQpBZ/homeopathy-2-2x-1.png',
        },
        {
          name: 'Psychology',
          image: 'https://i.postimg.cc/fLRCQpBZ/homeopathy-2-2x-1.png',
        },
      ],
    }
  },
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
</style>
