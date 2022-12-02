<template>
  <div class="main-div bg-no-repeat bg-cover pb-20">
    <div class="lifecycle-text text-center not-italic font-extrabold p-12">
      LIFECYCLE COST OF A DISEASE
    </div>
    <div class="lg:flex justify-around flex-row items-center flex-wrap">
      <div>
        <div class="image">
          <div class="relative text-center text-white">
			<div>
				<img
				class="rect relative"
				src="../assets/images/Rectangle 9.png"
				alt="DirectCost"
				/>
			</div>
            <div
              class="
                cost-text
                absolute
                top-1/2
                left-1/2
                transform
                -translate-x-1/2 -translate-y-1/2
                font-semibold
                text-2xl
                not-italic
              "
            >
              Direct Cost
            </div>
          </div>
          <div class="text-center pt-4 text-lg font-normal">Healthcare & Medical Cost</div>
        </div>
      </div>
      <div class="signs font-semibold text-3xl not-italic text-center">+</div>
      <div>
        <div class="relative text-center text-white">
          <img
            class="rect"
            src="../assets/images/Rectangle 10.png"
            alt="IndirectCost"
          />
          <div
            class="
              cost-text
              absolute
              top-1/2
              left-1/2
              transform
              -translate-x-1/2 -translate-y-1/2
              font-semibold
              text-2xl
              not-italic
            "
          >
            InDirect Cost
          </div>
        </div>
        <div class="text-center pt-4 text-lg font-normal">Decrease quality of life, pain, <br /> anxiety, incovenience &</div>
      </div>
      <div class="signs font-semibold text-3xl not-italic text-center">+</div>
      <div>
        <div class="relative text-center text-white">
          <img
            class="rect"
            src="../assets/images/Rectangle 11.png"
            alt="IntagibleCost"
          />
          <div
            class="
              cost-text
              absolute
              top-1/2
              left-1/2
              transform
              -translate-x-1/2 -translate-y-1/2
              font-semibold
              not-italic
              text-2xl
            "
          >
            Intangible Cost
          </div>
        </div>
        <div class="text-center pt-4 text-lg font-normal">Decrease quality of life, <br /> pain, anxiety, <br /> incovenience &</div>
      </div>
      <div class="signs font-semibold text-3xl not-italic text-center">=</div>
      <div >
        <div class="relative text-center text-white">
          <img
            class="rect"
            src="../assets/images/Rectangle 12.png"
            alt="TotalCosr"
          />
          <div
            class="
              cost-text
              absolute
              top-1/2
              left-1/2
              transform
              -translate-x-1/2 -translate-y-1/2
              font-semibold
              text-2xl
              not-italic
            "
          >
            Total Cost
          </div>
        </div>
        <div class="text-center pt-4 text-lg font-normal">Decrease quality of life, pain, <br /> anxiety, incovenience &</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'LifecycleCost',
}
</script>

<style scoped>
.main-div {
  background-image: url('../assets/images/diverse-people-working-office 1.png');
}

.lifecycle-text {
  font-size: 28px;
  line-height: 34px;
}

.rect {
  position: relative;
  border-radius: 19px;
  margin: auto;
}

.cost-details {
  font-style: normal;
  font-weight: 500;
  font-size: 18px;
  line-height: 22px;
}

/* .image ::after {
	background: rgba(0 0 0 / 50%);
	position: absolute;
	width: 100%;
	height: 100%;
	top: 0;
	left: 0;
	content: '';
} */
</style>
