<template id="">
  <nuxt-link to="/login">
    <section
      id="mainBody"
      class="hero is-fullheight has-text-white">
      <div class="hero-body splash_screen_background ">
        <div class="container has-text-centered">
          <div class="container">
            <img
              id="mainLogo"
              src="~assets/images/mec-logo-quick-save.png"
              alt="">
          </div>
          <div class="container ">
            <h1
              id="splash-title"
              class="is-size-4 has-text-weight-bold verticalPadding">
              Medgar Evers College, CUNY
            </h1>
            <p
              id="splash-subtitle"
              class="is-size-6">
              STUDENT LIFE AT YOUR <br>
              FINGERTIPS
            </p>
          </div>



          <p class="is-size-6 has-text-centered has-text-grey-light text-fix">
            The energy and excitement of a school on the rise.
            Our Central Brooklyn campus, just steps away from
            the Brooklyn Botanical Garden and the Brooklyn
            Museum, is in the midst of the borough’s cultural and
            economic renaissance.
          </p>
        </div>
      </div>
    </section>
  </nuxt-link>
</template>

<style media="screen">
.splash_screen_background {
  background: url('~assets/images/black_gradient.jpeg') no-repeat;
  height: 100%;
  width: 100%;
  background-size: cover;
}

#mainLogo {
  border-radius: 10px;
}

#splash-title {
  padding: 20px 0px;
}

#splash-subtitle {
  padding-bottom: 35px;
  line-height: 1;
}

.text-fix {
  line-height: 1;
}
</style>
