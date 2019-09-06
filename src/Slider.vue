<template>
  <div id="app">
    <tiny-slider
      :mouse-drag="true"
      :loop="true"
      :autoplay="true"
      :autoplay-button-output="false"
      :speed="500"
      :controls="false"
      items="3"
      gutter="20"
    >
      <img alt="Slider 1" src="./assets/map-gallery-img-1.jpg" />      
      <img alt="Slider 1" src="./assets/video-img-1-1100x550.jpg" />
      <img alt="Slider 2" src="./assets/map-gallery-img-2.jpg" />
      <img alt="Slider 1" src="./assets/video-img-2-1100x550.jpg" />
      <img alt="Slider 3" src="./assets/map-gallery-img-3.jpg" />
      <img alt="Slider 1" src="./assets/video-img-3-1100x550.jpg" />
      <img alt="Slider 4" src="./assets/map-gallery-img-4.jpg"  />
    </tiny-slider>    
  </div>
</template>

<script>
import VueTinySlider from "vue-tiny-slider";

export default {
  name: "app",
  components: {
    "tiny-slider": VueTinySlider
  }
};
</script>

<style>
  #tns1 > .tns-item {
    padding-right: 0px !important;
    cursor: pointer;
  }
</style>