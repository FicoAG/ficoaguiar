<template>
  <div class="education-container">
    <h1>EDUCATION</h1>
    <div class="container">
      <div class="timeline-block timeline-block-right">
        <div class="marker"></div>
        <div class="timeline-content">
          <h3>FULL STACK DEVELOPER BOOTCAMP</h3>
          <span>Reboot Academy |</span>
          <span class="year">Sep 2019 - Dic 2019</span>
        </div>
      </div>
      <div class="timeline-block timeline-block-left">
        <div class="marker"></div>
        <div class="timeline-content">
          <h3>FULL STACK DEVELOPER BOOTCAMP</h3>
          <span>Le Wagon |</span>
          <span class="year">Apr 2019 - Jun 2019</span>
        </div>
      </div>
      <div class="timeline-block timeline-block-right">
        <div class="marker"></div>
        <div class="timeline-content">
          <h3>EXECUTIVE MASTER ON BUSINESS ADMINISTRATION - EMBA</h3>
          <span>Mid Atlantic Business School |</span>
          <span class="year">Jan 2018 - Dec 2018</span>
        </div>
      </div>
      <div class="timeline-block timeline-block-left">
        <div class="marker"></div>
        <div class="timeline-content">
          <h3>BACHELOR OF BUSINESS ADMINISTRATION, INTERNATIONAL TRADE & MARKETING</h3>
          <span>University of Wales |</span>
          <span class="year">2000 - 2005</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
  outline: none;
}

body {
  margin: 0;
  padding: 30px 0;
  font-family: 'Roboto', sans-serif;
  background: #f1f2f6;
}

h1 {
  text-align: center;
  font-weight: 300;
  color: white;
  font-size: 36px;
}

h1 span {
  font-weight: 600;
}

.container {
  width: 80%;
  padding: 50px 0;
  margin: 50px auto;
  position: relative;
  overflow: hidden;
}

.container:before {
  content: '';
  position: absolute;
  top: 0;
  left: 50%;
  margin-left: -1px;
  width: 2px;
  height: 100%;
  background: #ccd1d9;
  z-index: 1;
}

.timeline-block {
  width: -webkit-calc(50% + 8px);
  width: -moz-calc(50% + 8px);
  width: calc(50% + 8px);
  display: -webkit-box;
  display: -webkit-flex;
  display: -moz-box;
  display: flex;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -moz-box-pack: justify;
  justify-content: space-between;
  clear: both;
}

.timeline-block-right {
  float: right;
}

.timeline-block-left {
  float: left;
  direction: rtl;
}

.marker {
  width: 16px;
  height: 16px;
  border-radius: 50%;
  border: 2px solid #f5f7fa;
  background: #d84f00;
  margin-top: 10px;
  z-index: 9999;
}

.timeline-content {
  width: 95%;
  padding: 0 15px;
  color: white;
}

.timeline-content h3 {
  margin-top: 5px;
  margin-bottom: 5px;
  font-size: 22px;
  font-weight: 500;
}

.timeline-content span {
  font-size: 15px;
  color: #d84f00;
}
.year {
  color: #d84f00 !important;
}

.timeline-content p {
  font-size: 14px;
  line-height: 1.5em;
  word-spacing: 1px;
  color: #888;
}

@media screen and (max-width: 768px) {
  .container:before {
    left: 8px;
    width: 2px;
  }
  .timeline-block {
    width: 100%;
    margin-bottom: 30px;
  }
  .timeline-block-right {
    float: none;
  }

  .timeline-block-left {
    float: none;
    direction: ltr;
  }
}

.education-container {
  padding-top: 40px;
  background-color: black;
  padding-bottom: 40px;
}
</style>
