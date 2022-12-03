<template>
  <div id="app">
    <Navbar />
    <RequestDemo />
    <TrustedBy />
    <LifeCycle />
    <Naturally />
    <HolisticWellness />
    <h4 class="m-8 font-bold text-2xl text-center">HEALTH PLAN</h4>
    <HealthPlan :image='image1' :header='header1' />
    <HealthPlan :image='image2' :header='header2' :active-color=activeColor :color=color :image-position=imagePosition />
    <HealthPlan :image='image3' :header='header3'/>
    <HowDoes />
    <WhatWeOffer />
    <CompleteDashboard />
    <Footer />
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  data() {
	return {
		image1: 'https://i.postimg.cc/SxKNbsqP/Rectangle-29.png',
		image2: 'https://i.postimg.cc/1XwTdbvB/Rectangle-31.png',
		image3: 'https://i.postimg.cc/9XdJvPWL/Rectangle-33.png',
		header1: 'Heal',
		header2: 'ENGAGE',
		header3: 'STAY FIT',
		activeColor: '#FBFEE9',
		color: '#2C2C2C',
		imagePosition: true
	}
  }
}
	// https://ibb.co/sK3kxbx
	// https://ibb.co/mFSHx73
	// https://ibb.co/37fqNvq
</script>

<style scoped>
#app {
  font-family: Inter, sans-serif;
  color: #284948;
}
</style>

