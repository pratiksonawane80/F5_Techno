<template>
  <div class="main-div lg:mb-40 lg:flex h-96 justify-center">
    <div class="w-1/2 mt-10 laptop"></div>
    <div class="mt-10 lg:mr-40">
      <div
        class="
          font-bold
          head-text
          text-white
          mb-4
          lg:text-left
          text-center
          lg:p-0
          py-10
        "
      >
        <p>COMPLETE</p>
        <p>DASHBOARD FOR</p>
        <p>YOUR COMPANY</p>
        <Button />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'CompleteDashboard',
}
</script>

<style scoped>
.main-div {
  background: linear-gradient(90.05deg, #284948 1.22%, #141414 98.84%);
  background-size: 100% 300px;
  background-repeat: no-repeat;
}

.laptop {
  background-image: url('../assets/images/Group 675 1.png');
  background-repeat: no-repeat;
}

.head-text {
  font-size: 32px;
}

img {
  margin-left: auto;
  margin-right: auto;
  display: block;
}
</style>
