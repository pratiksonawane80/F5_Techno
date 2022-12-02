<template>
  <div v-if="windowWidth > 1100">
    <div class="navbar flex flex-row items-center">
      <ul class="nav-menu inline-flex w-full items-center justify-end">
        <li class="nav-item">
          <nuxt-link class="nav-link hover:cursor-pointer" to="/">
            Our Products
          </nuxt-link>
        </li>
        <li class="nav-item">
          <nuxt-link class="nav-link hover:cursor-pointer" to="/">
            For Engineers
          </nuxt-link>
        </li>
        <li class="nav-item">
          <nuxt-link class="nav-link hover:cursor-pointer" to="/">
            Multi Vitamins
          </nuxt-link>
        </li>
        <li class="nav-item">
          <nuxt-link class="nav-link hover:cursor-pointer" to="/">
            Buy
          </nuxt-link>
        </li>
        <li class="nav-item">
          <nuxt-link class="nav-link hover:cursor-pointer" to="/">
            Books
          </nuxt-link>
        </li>
        <li class="nav-item-btn">
          <button class="sign-in">Sign in/Sign up</button>
        </li>
      </ul>
    </div>
  </div>
  <div v-else>
    <section class="top-nav">
      <div></div>
      <input id="menu-toggle" type="checkbox" />
      <label class="menu-button-container" for="menu-toggle">
        <div class="menu-button"></div>
      </label>
      <ul style="padding-bottom:60px" class="menu">
        <li>Our Products</li>
        <li>For Engineers</li>
        <li>Multi vitamins</li>
        <li>Buy</li>
        <li>Books</li>
		<li>Sign in/Sign up</li>

      </ul>
    </section>
  </div>
</template>

<script>
export default {
  name: 'TheNavbar',

  data() {
    return {
      windowWidth: 0,
    }
  },

  beforeMount() {
    this.windowWidth = document.documentElement.clientWidth
  },
}
</script>

<style scoped>
.navbar {
  box-shadow: 0 4px 15px 2px rgba(0 0 0 / 10%);
  transition: all 0.4s ease-in-out;
}

.nav-menu {
  padding-right: 47px;
}

.nav-item {
  margin: 30px;
}

.nav-link {
  color: #5a5a5a;
  font-size: 16px;
}

.sign-in {
  font-size: 15px;
  background-color: #dcdcdc;
  border-radius: 7px;
  width: 165px;
  height: 46px;
}

/* ///////////////// */

h2 {
  vertical-align: center;
  text-align: center;
}

html, body {
  margin: 0;
  height: 100%;
}

.top-nav {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
  background-color: #F28737;
  color: #FFF;
  height: 50px;
  padding: 1em;
}

.menu {
  display: flex;
  flex-direction: row;
  list-style-type: none;
  margin: 0;
  padding: 0;
}

.menu > li {
  margin: 0 1rem;
  padding: auto;
  overflow: hidden;
}

.menu-button-container {
  display: none;
  height: 100%;
  width: 30px;
  cursor: pointer;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

#menu-toggle {
  display: none;
}

.menu-button,
.menu-button::before,
.menu-button::after {
  display: block;
  background-color: #fff;
  position: absolute;
  height: 4px;
  width: 30px;
  transition: transform 400ms cubic-bezier(0.23, 1, 0.32, 1);
  border-radius: 2px;
}

.menu-button::before {
  content: '';
  margin-top: -8px;
}

.menu-button::after {
  content: '';
  margin-top: 8px;
}

#menu-toggle:checked + .menu-button-container .menu-button::before {
  margin-top: 0;
  transform: rotate(405deg);
}

#menu-toggle:checked + .menu-button-container .menu-button {
  background: rgba(242 135 55 / 0%)
}

#menu-toggle:checked + .menu-button-container .menu-button::after {
  margin-top: 0;
  transform: rotate(-405deg);
}

@media (max-width: 700px) {
  .menu-button-container {
    display: flex;
  }

  .menu {
    position: absolute;
    top: 0;
    margin-top: 50px;
    left: 0;
    flex-direction: column;
    width: 100%;
    justify-content: center;
    align-items: center;
  }

	  .menu > li {
		display: flex;
		justify-content: center;
		margin: 0;
		padding: 0.5em 0;
		width: 100%;
		color: white;
		background-color: #F28737;
	  }

  #menu-toggle ~ .menu li {
    height: 0;
    margin: 0;
    padding: 0;
    border: 0;
    transition: height 400ms cubic-bezier(0.23, 1, 0.32, 1);
  }


  #menu-toggle:checked ~ .menu li {
    height: 2.5em;
    padding: 0.5em;
    transition: height 400ms cubic-bezier(0.23, 1, 0.32, 1);
  }

  .menu li :hover {
	color: black;
  }


}
</style>
