<template>
  <div class="main-div lg:mb-40 lg:flex justify-center">
    <div class="w-1/2 mt-10">
      <img src="../assets/images/Group 675 1.png" alt="" />
    </div>
    <div class="mt-10 mr-40">
      <div class="font-bold head-text text-white mb-4">
        COMPLETE <br />
        DASHBOARD FOR <br />
        YOUR COMPANY
      </div>
      <div>
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
  height: auto;
  background: linear-gradient(90.05deg, #284948 1.22%, #141414 98.84%);
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
