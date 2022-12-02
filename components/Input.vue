<template>
	<div>
		<input class="input-field text-center" type="email" placeholder="Enter Your Email"><button class="enter-btn"><img class="inline" src="../assets/images/Vector 9.png" alt=""></button>
	</div>
</template>

<script>
export default {
	name: 'TheInput'
}
</script>

<style scoped>
	.input-field {
		height: 55px;
		background: #FFF;
		border-radius: 7px 0 0 7px;
	}

	.enter-btn {
		width: 52px;
		height: 55px;
		background: #F28737;
		border-radius: 0 7px 7px 0;
	}
</style>
