<template>
  <div main-div>
	<div class="m-8 font-bold health-text text-center">
		HEALTH PLAN
	</div>
    <!-- First -->
    <div class="flex flex-auto relative">
      <div class="w-screen heal w-1/2">
	  <div class="p-20">
        <div class="font-bold heal-text mb-5">HEAL</div>
        <div>
          <ul class="list-disc	text-white">
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
		<img class="absolute center-img top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2" src="../assets/images/alternative-medicine@2x 1.png" alt="">
	  </div>

	  <div class="image w-screen bg-cover w-1/2	">
	  </div>
    </div>
    <!-- Secomd -->
    <div class="flex flex-auto relative">


	  <div class="image2 w-screen bg-cover w-1/2	">
	  </div>

	  <div>
		<img class="absolute center-img top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2" src="../assets/images/alternative-medicine@2x 1.png" alt="">
	  </div>

      <div class="w-screen engage w-1/2">
	  <div class="p-20">
        <div class="font-bold engage-text mb-5">ENGAGE</div>
        <div class="">
          <ul class="list-disc engage-list">
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

    </div>
	    <!-- Third -->
        <div class="flex flex-auto relative">
      <div class="w-screen heal w-1/2">
	  <div class="p-20">
        <div class="font-bold heal-text mb-5">STAY FIT</div>
        <div>
          <ul class="list-disc	text-white">
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
		<img class="absolute center-img top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2" src="../assets/images/alternative-medicine@2x 1.png" alt="">
	  </div>

	  <div class="image3 w-screen bg-cover w-1/2	">
	  </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HealthPlan',
}
</script>

<style scoped>
.image {
	background-image: url('../assets/images/Rectangle 29.png');
}

.image2 {
	background-image: url('../assets/images/Rectangle 31.png');
}

.image3 {
	background-image: url('../assets/images/Rectangle 33.png');
}

.heal {
	background-color: #284948;
	height: auto;
}

.engage {
	background-color: #FBFEE9;
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
	color: #C3D797;
}

.engage-text {
	font-style: normal;
	font-weight: 700;
	font-size: 26px;
	line-height: 31px;
}

.engage-list {
	color: #2C2C2C;
}

.center-img {
	background-color: #FFF;
	padding: 12px;
	border-radius: 50%;
}
</style>
