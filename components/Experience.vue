<template>
  <div class="education-container">
    <h1>WORK EXPERIENCE</h1>
    <div class="container">
      <div class="timeline-block timeline-block-right">
        <div class="marker"></div>
        <div class="timeline-content">
          <h3>CHIEF SALES OFFICER</h3>
          <span>AdQuiver Media |</span>
          <span class="year">Sep 2018 - Jan 2019</span>
          <p>
            <bdi>Planning, leading and organizing the sales department goals and strategies. Design and implementation of new products. Responsible for key accounts.</bdi>
          </p>
        </div>
      </div>
      <div class="timeline-block timeline-block-left">
        <div class="marker"></div>
        <div class="timeline-content">
          <h3>SALES MANAGER</h3>
          <span>Rodamientos Gallardo |</span>
          <span class="year">May 2016 - Apr 2018</span>
          <p>
            <bdi>Developing and implementing sales strategies. Pricing. Route to market.</bdi>
          </p>
        </div>
      </div>
      <div class="timeline-block timeline-block-right">
        <div class="marker"></div>
        <div class="timeline-content">
          <h3>HOSPITALITY CUSTOMER MANAGER</h3>
          <span>Mahou - San Miguel |</span>
          <span class="year">Mar 2013 - Apr 2016</span>
          <p>
            <bdi>Developing and implementing sales strategies. Pricing. Route to market.</bdi>
          </p>
        </div>
      </div>
      <div class="timeline-block timeline-block-left">
        <div class="marker"></div>
        <div class="timeline-content">
          <h3>CHIEF SALES OFFICER</h3>
          <span>Tüv Sud Iberia |</span>
          <span class="year">Oct 2012 - Feb 2013</span>
          <p>
            <bdi>Responsible for new developments and deployment of NUMoS (National Used Car Monitoring System) web app.</bdi>
          </p>
        </div>
      </div>
      <div class="timeline-block timeline-block-right">
        <div class="marker"></div>
        <div class="timeline-content">
          <h3>VOLKSWAGEN & AUDI TRAINING MANAGER</h3>
          <span>Domingo Alonso Group |</span>
          <span class="year">Jan 2011- Sep 2012</span>
          <p>
            <bdi>Planning and execution of training programs for dealer networks. New products release. Innovation management.</bdi>
          </p>
        </div>
      </div>
      <div class="timeline-block timeline-block-left">
        <div class="marker"></div>
        <div class="timeline-content">
          <h3>CARIBBEAN MARKET MANAGER</h3>
          <span>Domingo Alonso Group |</span>
          <span class="year">Mar 2007 - Dec 2010</span>
          <p>
            <bdi>Customer acquisition and deal broker. Manufacturer relations . Logistics. Diplomatic and legal liaison.</bdi>
          </p>
        </div>
      </div>
      <div class="timeline-block timeline-block-right">
        <div class="marker"></div>
        <div class="timeline-content">
          <h3>PRODUCT MANAGER</h3>
          <span>Domingo Alonso Group |</span>
          <span class="year">Jan 2007 - Feb 2007</span>
          <p>
            <bdi>Volkswagen passenger car product manager.</bdi>
          </p>
        </div>
      </div>
      <div class="timeline-block timeline-block-left">
        <div class="marker"></div>
        <div class="timeline-content">
          <h3>SALES PLANNING</h3>
          <span>Domingo Alonso Group |</span>
          <span class="year">Jun 2005 - Dec 2005</span>
          <p>
            <bdi>Volkswagen passenger car sales planning.</bdi>
          </p>
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
  color: #777;
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
  color: #666;
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
}
</style>
