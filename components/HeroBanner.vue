<template>
  <div>
    <div class="hero-banner">
      <div class="hi-holder">- Hi, I am -</div>
      <div class="name-holder">
        <ti>Fico Aguiar</ti>
      </div>
      <div class="job-holder">Full-stack developer</div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.hero-banner {
  height: 100vh;
  justify-content: center;
  display: flex;
  align-items: center;
  flex-direction: column;
  // background-image: url('https://images.pexels.com/photos/826380/pexels-photo-826380.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260');
  background-image: url('https://images.pexels.com/photos/1438081/pexels-photo-1438081.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260');
  background-size: cover;
  background-position: center;
  background-color: rgb(53, 49, 104);
  background-blend-mode: lighten;
  @media screen and (max-width: 500px) {
    background-position: center;
  }
}

.name-holder {
  font-size: calc(16px + 3vh);
  // color: #c49d15;
  // #d84f00
  color: #d84f00;
  margin-top: -1.4rem;
  font-family: 'Roboto', sans-serif !important;
  font-weight: 900;
  // text-shadow: 2px 2px #232420a1;
  @media screen and (max-width: 500px) {
    font-size: 22px;
  }
}

.job-holder {
  font-size: calc(12px + 1.2vh);
  // color: #c49d15;
  color: white;
  font-family: 'Courier Prime', monospace;
  margin-top: -1rem;
  @media screen and (max-width: 500px) {
    font-size: 18px;
    margin-top: -10px;
  }
}
.hi-holder {
  font-size: calc(12px + 2vh);
  // color: #c49d15;
  color: white;
  font-family: 'Courier Prime', monospace;
  @media screen and (max-width: 500px) {
    font-size: 18px;
    margin-top: -10px;
  }
}
</style>
