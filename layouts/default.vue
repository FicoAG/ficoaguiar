<template>
  <div>
    <!-- <b-navbar>
      <template slot="brand">
        <b-navbar-item tag="router-link" :to="{ path: '/' }">
          <img
            src="https://raw.githubusercontent.com/buefy/buefy/dev/static/img/buefy-logo.png"
            alt="Lightweight UI components for Vue.js based on Bulma"
          />
        </b-navbar-item>
      </template>
      <template slot="start">
        <b-navbar-item href="#">
          Home
        </b-navbar-item>
        <b-navbar-item href="#">
          Documentation
        </b-navbar-item>
        <b-navbar-dropdown label="Info">
          <b-navbar-item href="#">
            About
          </b-navbar-item>
          <b-navbar-item href="#">
            Contact
          </b-navbar-item>
        </b-navbar-dropdown>
      </template>

      <template slot="end">
        <b-navbar-item tag="div">
          <div class="buttons">
            <a class="button is-primary">
              <strong>Sign up</strong>
            </a>
            <a class="button is-light">
              Log in
            </a>
          </div>
        </b-navbar-item>
      </template>
    </b-navbar>-->
    <nuxt />

    <footer class="footer">
      <div class="content has-text-centered">
        <a href="https://www.linkedin.com/in/ficoaguiar/" target="_blank">
          <b-icon class="the-icon" icon="linkedin-box" size="is-medium" type="is-white"></b-icon>
        </a>
        <a href="http://github.com/ficoAG/" target="_blank">
          <b-icon class="the-icon" icon="github-box" size="is-medium" type="is-white"></b-icon>
        </a>
        <a href="mailto:registros.web@icloud.com?subject=Web Contact&body=Hola Fico.">
          <b-icon class="the-icon" icon="at" size="is-medium" type="is-white"></b-icon>
        </a>
        <div class="copy">
          <p>FICO AGUIAR ©2019</p>
          <div class="contact"></div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {}
</script>
<style lang="scss" scoped>
footer {
  background-color: rgb(36, 36, 36);
  color: white;
  font-family: 'Roboto', sans-serif;
  font-weight: lighter;
}

.the-icon {
  padding: 30px;
  background-color: rgb(61, 61, 61);
  margin: 10px;
}
.copy {
  margin-top: 30px;
  color: rgb(112, 112, 112);
}

.contact {
  display: flex;
  width: 20%;
  margin: 0 auto;
  justify-content: center;
  p {
    margin: 0 5px;
  }
}
</style>
