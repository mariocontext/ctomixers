<template>

  <header role="banner">

        <nav class="navbar main-navbar" role="navigation" aria-label="main navigation">
            <div class="navbar-brand">
              <router-link class="navbar-item logo" lang="en" to="/">
                    <img src="~static/images/cto_mixers_logo_color.png" alt="CTO Mixer logo with graphics of drinking glasses">
              </router-link>
              <a role="button" class="navbar-burger" v-on:click="toggleMenu" v-bind:class="{ 'is-active': menuActive }" aria-label="menu" aria-expanded="false">
                <div>
                  <span aria-hidden="true"></span>
                  <span aria-hidden="true"></span>
                  <span aria-hidden="true"></span>
                </div>
              </a>
            </div>

              <div class="navbar-menu" v-bind:class="{ 'is-active': menuActive }">
                <span class="navbar-start">
                  <router-link class="navbar-item" lang="en" to="/" v-on:click.native="toggleMenu">Home</router-link>
                  <router-link class="navbar-item" lang="en" to="/services" v-on:click.native="toggleMenu">Services</router-link>
                  <router-link class="navbar-item" lang="en" to="/faq" v-on:click.native="toggleMenu">FAQ</router-link>
                  <router-link class="navbar-item" lang="en" to="/about" v-on:click.native="toggleMenu">About</router-link>
                  <router-link class="navbar-item" lang="en" to="/contact" v-on:click.native="toggleMenu">Contact</router-link>

                </span>
                <span class="navbar-end">
                </span>
              </div>
        </nav>   
  </header>

</template>



<script>

  
  module.exports = {

    data: function() {
      return {
        menuActive: false
      }
    },
    methods: {
      toggleMenu: function() {
        this.menuActive= !this.menuActive
      }
    }
    
  }

</script>



<style lang="scss" scoped>

.main-navbar a {
  transition: all 0.5s ease;
    &:hover {
      color: #0192FF;
      background-color: #000;
  }
}

nav .navbar-item.nuxt-link-exact-active {
  color: #0192FF;
}
header {
  position: fixed;
  top: 0;
  width: 100%;
  z-index: 1000;
}

nav {

  background: #000;
  font-size: 1.2rem;

  .navbar-menu.is-active {
    width: 100%;
  }

  .navbar-brand {
    margin: 0 auto;
  }

  .navbar-item {
    color: #FFF;
    padding: 2rem;
  }

  .navbar-start .navbar-item {
    border-bottom: 1px solid #333;
  }

}

.navbar-burger {
  align-self: center;
  margin-right: 1rem;
  span {
    height: 3px;
  }
}

.main-navbar {
  opacity: .85;
}

</style>