<template>
  <div class="main-div bg-no-repeat bg-cover lg:p-20 p-5">
    <div class="what-offer font-bold text-center not-italic lg:pb-16">
      WHAT WE OFFER
    </div>
    <div
      class="
        grid
        lg:grid-rows-3
        grid-cols-0 grid-flow-col
        gap-16
        lg:overflow-y-hidden
        overflow-y-scroll
      "
    >
      <div
        v-for="data in dataArr"
        :key="data.image"
        class="relative text-center lg:flex justify-center items-center"
      >
        <div class="icon-wrapper relative">
          <img
            class="
              absolute
              top-1/2
              left-1/2
              transform
              -translate-x-1/2 -translate-y-1/2
            "
            :src="data.image"
            alt=""
          />
        </div>
        <p class="goal-text text-center mx-4 text-lg font-semibold">
          {{ data.text }}
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'WhatWeOffer',
  data() {
    return {
      dataArr: [
        {
          text: 'Lorem ipsum',
          image: 'https://i.postimg.cc/524z6LWN/goal-1.png',
        },
        {
          text: 'Lorem ipsum',
          image: 'https://i.postimg.cc/524z6LWN/goal-1.png',
        },
        {
          text: 'Lorem ipsum',
          image: 'https://i.postimg.cc/524z6LWN/goal-1.png',
        },
        {
          text: 'Lorem ipsum',
          image: 'https://i.postimg.cc/t4JgK5HP/pyramid-2x-1.png',
        },
        {
          text: 'Lorem ipsum',
          image: 'https://i.postimg.cc/t4JgK5HP/pyramid-2x-1.png',
        },
        {
          text: 'Lorem ipsum',
          image: 'https://i.postimg.cc/Yqs7WBJG/doctor-1.png',
        },
        {
          text: 'Lorem ipsum',
          image: 'https://i.postimg.cc/Yqs7WBJG/doctor-1.png',
        },
        {
          text: 'Lorem ipsum',
          image: 'https://i.postimg.cc/t4JgK5HP/pyramid-2x-1.png',
        },
        {
          text: 'Lorem ipsum',
          image: 'https://i.postimg.cc/524z6LWN/goal-1.png',
        },
        {
          text: 'Lorem ipsum',
          image: 'https://i.postimg.cc/524z6LWN/goal-1.png',
        },
        {
          text: 'Lorem ipsum',
          image: 'https://i.postimg.cc/t4JgK5HP/pyramid-2x-1.png',
        },
      ],

      // https://i.postimg.cc/524z6LWN/goal-1.png goal1
      // https://i.postimg.cc/t4JgK5HP/pyramid-2x-1.png pyramid
      // https://i.postimg.cc/Yqs7WBJG/doctor-1.png doctor
    }
  },
}
</script>

<style scoped>
.main-div {
  background-image: url('../assets/images/5333978 1.png');
  height: auto;
  max-height: auto;
}

.what-offer {
  font-size: 26px;
}

.child {
  flex: 1 0 21%;
  margin: 5px;
  height: 100px;
  background-color: blue;
}

.icon-wrapper {
  width: 103px;
  height: 103px;
  background: #d2e289;
  border-radius: 5px;
}

.goal-text {
  color: #2c2c2c;
}
</style>
