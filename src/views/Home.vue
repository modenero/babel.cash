<template>
    <main>
        <!-- Scrolling background -->
        <div class="content-bg-wrap"></div>

        <div class="header--standard header--standard-landing" id="header--standard">
            <div class="container">
                <div class="header--standard-wrap">

                    <a href="javascript://" class="logo">
                        <div class="img-wrap">
                            <img src="img/logo.png" alt="Olympus">
                            <img src="img/logo-colored-small.png" alt="Olympus" class="logo-colored">
                        </div>

                        <div class="title-block">
                            <h6 class="logo-title">Babel.cash</h6>
                            <div class="sub-title">Let's Talk Cash Money!</div>
                        </div>
                    </a>

                    <a href="javascript://" class="open-responsive-menu js-open-responsive-menu">
                        <svg class="olymp-menu-icon">
                            <use xlink:href="svg-icons/sprites/icons.svg#olymp-menu-icon"></use>
                        </svg>
                    </a>

                    <div class="header-menu">
                        <div class="float-right">
                            <router-link to="/chat">Sign in</router-link>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <div class="header-spacer--standard"></div>

        <div class="container">
            <div class="row display-flex">
                <div class="col col-xl-6 col-lg-6 col-md-12 col-sm-12 col-12">
                    <div class="landing-content">
                        <h1>Welcome to the Biggest Social Network in the World</h1>

                        <p>
                            We are the best and biggest social network with 5 billion active users all around the world. Share you
                            thoughts, write blog posts, show your favourite music via Stopify, earn badges and much more!
                        </p>

                        <a href="javascript://" class="btn btn-md btn-border c-white">Register Now!</a>
                    </div>
                </div>
            </div>
        </div>
    </main>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    // HelloWorld
  }
}
</script>

<style scoped>
.header-menu {

}
</style>
