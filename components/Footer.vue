<template>
	<div class="main-div lg:flex text-white justify-around lg:text-left text-center">
		<div class="text-white lg:p-10 p-4">
			<div class="text-lg	font-extrabold	ml-6">Reach Out to Us</div>
			<div class="text-lg	font-normal ml-6">Lorem epsum Pvt Ltd.</div>

		<div class="mt-10 font-normal text-base">
			<p>
				<img class="inline	" src="../assets/images/circle.png" alt=""> &nbsp;Lorem ipsum dolor sit amet, consectetur <br /> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; adipiscing elit. Lorem ipsum dolor sit amet, <br /> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; consectetur adipiscing elit.
			</p>
			<p class=" mt-5">
				<img class="inline" src="../assets/images/Vector 189.png" alt=""> &nbsp;+91452547452
			</p>
			<p class="mt-5">
				<img class="inline" src="../assets/images/Subtract.png" alt=""> &nbsp;loremepsum@gmail.com
			</p>
		</div>
		</div>

		<div class="lg:mt-28 mt-8">
			<ul>
				<p class="font-bold text-lg"> About</p>
				<li>Contact Us</li>
				<li>About Us</li>
				<li>Careers</li>
				<li>Blogs</li>
				<li>Sitemap</li>
				<li>Map Account</li>
			</ul>
		</div>

		<div class="lg:mt-28 mt-8">
			<ul>
				<p class="font-bold text-lg">Policy Info</p>
				<li>Terms of Use</li>
				<li>Return Policy</li>
			</ul>
		</div>

		<div class="lg:mt-28 mt-8">
			<ul>
				<p class="font-bold text-lg">Need Help?</p>
				<li>FAQs</li>
				<li>Online Support</li>
				<li>Customer Support</li>
				<li><Button class="mt-10" /></li>
			</ul>
		</div>

		<div class="lg:mt-28 mt-8">
			<ul>
				<p class="font-bold text-lg">Subscribe Our Newsletter</p>
				<li class="my-5"><Input /></li>
				<li>Register now to get updates on <br /> promotions and coupons or <br /> Download App</li>
				<li class="copyright mt-20 mb-10">@ Copyright 2021 UniteCloud</li>
			</ul>
		</div>
	</div>
</template>

<script>
export default {
	name: "TheFooter"
}
</script>	

<style scoped>
	.main-div {
		background-color: #284948;
	}

	li {
		font-style: normal;
		font-weight: 400;
		font-size: 16px;
		margin: 5px 0
	}

	.copyright {
		margin-top: 107px;
		margin-bottom: 30px
	}

/*
	.request-btn {
		width: 170px;
		text-align: center;
		height: 38px;
		background: #f28737;
		font-size: 15px;
		border-radius: 7px;
	} */
</style>
