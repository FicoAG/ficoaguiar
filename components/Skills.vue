<template>
  <div>
    <div class="main-container">
      <h1>SKILLS</h1>
      <div class="skills-container">
        <div class="wraper">
          <div class="bar V75" data-skill="JavaScript"></div>
          <div class="bar V50" data-skill="TypeScript"></div>
          <div class="bar V60" data-skill="Ruby"></div>
          <div class="bar V65" data-skill="HTML"></div>
          <div class="bar V60" data-skill="CSS"></div>
          <div class="bar V60" data-skill="VUE"></div>
          <div class="bar V50" data-skill="NUXT"></div>
          <div class="bar V40" data-skill="React"></div>
          <div class="bar V65" data-skill="Ruby on Rails"></div>
        </div>
        <div class="wraper">
          <div class="bar V55" data-skill="PostgreSQL"></div>
          <div class="bar V50" data-skill="MongoDB"></div>
          <div class="bar V60" data-skill="Git & Git Hub"></div>
          <div class="bar V65" data-skill="UI/UX Design"></div>
          <div class="bar V60" data-skill="Photoshop"></div>
          <div class="bar V60" data-skill="Ilustrator"></div>
          <div class="bar V50" data-skill="Servers"></div>
          <div class="bar V60" data-skill="Networks"></div>
          <div class="bar V100" data-skill="Techie"></div>
        </div>
      </div>
    </div>
    <h1>OTHERS</h1>
    <b-taglist class="tag-list">
      <b-tag type="is-primary is-medium">API Rest</b-tag>
      <b-tag type="is-primary is-medium">Express</b-tag>
      <b-tag type="is-primary is-medium">Bootstrap</b-tag>
      <b-tag type="is-primary is-medium">Vuetify</b-tag>
      <b-tag type="is-primary is-medium">Nodemon</b-tag>
      <b-tag type="is-primary is-medium">Figma</b-tag>
      <b-tag type="is-primary is-medium">Windows</b-tag>
      <b-tag type="is-primary is-medium">Linux</b-tag>
      <b-tag type="is-primary is-medium">MacOS</b-tag>
      <b-tag type="is-primary is-medium">Hostings</b-tag>
      <b-tag type="is-primary is-medium">Domains</b-tag>
    </b-taglist>
    <h1>LANGUAGES</h1>
    <div class="lang-container">
      <img class="flag" src="../static/spain.svg" alt />
      <img class="flag" src="../static/united-kingdom.svg" alt />
      <img class="flag" src="../static/france.svg" alt />
    </div>
  </div>
</template>

<script>
export default {}
</script>
<style lang="scss" scoped>
body {
  font-family: 'Roboto', sans-serif;
}

.flag {
  height: 48px;
  margin: 10px;
}

.tag-list {
  width: 60%;
  margin: 0 auto;
  justify-content: center;
}

h1 {
  font-family: 'Roboto', sans-serif;
  text-align: center;
  font-weight: 300;
  font-size: 36px;
  padding-bottom: 40px;
  padding-top: 40px;
}

.skills-container {
  width: 80%;
  display: flex;
  margin: 0 auto;
  justify-content: space-evenly;
}

.lang-container {
  width: 80%;
  display: flex;
  margin: 0 auto;
  justify-content: center;
}

.wraper {
  width: 30%;
  padding-bottom: 40px;
}

@keyframes load {
  from {
    width: 0%;
  }
}
@-webkit-keyframes load {
  from {
    width: 0%;
  }
}
@-moz-keyframes load {
  from {
    width: 0%;
  }
}
@-o-keyframes load {
  from {
    width: 0%;
  }
}

.bar {
  background-color: #eee;
  margin-bottom: 10px;
  font-size: 14px;
  color: #fff;
  font-weight: light;
  font-family: 'Roboto', sans-serif;
}
.bar::before {
  content: attr(data-skill);
  background-color: #d84f00;
  display: inline-block;
  padding: 5px 0 5px 10px;
  border-radius: 0px;
  animation: load 2s 0s;
  -webkit-animation: load 2s 0s;
  -moz-animation: load 2s 0s;
  -o-animation: load 2s 0s;
}

.bar.V100::before {
  width: calc(100%);
}

.bar.V75::before {
  width: calc(75%);
}

.bar.V65::before {
  width: calc(65%);
}

.bar.V60::before {
  width: calc(60%);
}

.bar.V55::before {
  width: calc(55%);
}

.bar.V50::before {
  width: calc(50%);
}

.bar.V40::before {
  width: calc(40%);
}
</style>
