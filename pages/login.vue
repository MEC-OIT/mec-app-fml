<template id="">
  <section class="hero is-fullheight ">
    <div class="hero-body login_screen_background">
      <div class="container">
        <div class="container has-text-centered">
          <img
            id="mec_logo"
            class="is-3by2"
            src="~assets/images/mec_logo.png"
            height="300px"
            width="200px"
            alt="">
        </div>
        <div class="field">
          <p class="control has-icons-left has-icons-right">
            <input
              class="input is-large transparent"
              type="email"
              placeholder="Email Address">
            <span class="icon is-small is-left">
              <i class="fas fa-envelope"/>
            </span>
          </p>
        </div>
        <div class="field ">
          <p class="control has-icons-left">
            <input
              class="input is-large transparent"
              type="password"
              placeholder="Password">
            <span class="icon is-small is-left">
              <i class="fas fa-lock"/>
            </span>
          </p>
        </div>
        <div class="loginContainer">
          <nuxt-link to="/main-menu">
            <button
              class=" loginButton button is-rounded is-large is-fullwidth is-size-5">
              LOGIN
            </button>
          </nuxt-link>
        </div>
        <div class="container has-text-centered createAccountContainer ">
          <nuxt-link to="/create-account">
            <a class="createAccount">
              Create Account
            </a>
          </nuxt-link>
        </div>
      </div>
    </div>
  </section>
</template>

<style media="screen">
.login_screen_background {
  background: url('~assets/images/mec_library.jpg') no-repeat;
  height: 100%;
  width: 100%;
  background-position: center;
  background-size: cover;
}

#mec_logo {
  position: relative;
  bottom: 10vh;
}

.transparent {
  background: rgba(255, 255, 255, 0.5);
  border: none;
  color: black;
}

.transparent::placeholder {
  color: #171d22;
  font-size: 20px;
}

.fas {
  color: #171d22;
}

.loginButton {
  background-color: $primary;
  border: none;
  outline: none;
  color: white;
}

.createAccount {
  color: $primary;
  padding: 25px;
  position: relative;
}

.createAccountContainer {
  margin: 25px;
}

.loginContainer {
  margin: 25px 0px;
}
</style>
