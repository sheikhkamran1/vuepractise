<template>
    <div>
        <div class="container-fluid">
          <div class="row">
      <VueSlickCarousel :arrows="true" :dots="true"  v-bind="settings">
        <card-component-view :image="`https://cdn.pixabay.com/photo/2023/01/14/10/18/buildings-7717853__340.jpg`" :title="`DEMO 1`" />
            <!-- <div class="col-md-12 bg-success">
              <img src="https://images.pexels.com/photos/5525050/pexels-photo-5525050.jpeg?auto=compress&cs=tinysrgb&w=600&lazy=load" alt="" >
            </div>
            <div class="col-md-12 bg-success">
              <img src="https://images.pexels.com/photos/15186505/pexels-photo-15186505.jpeg?auto=compress&cs=tinysrgb&w=600&lazy=load" alt="" >
            </div>
            <div class="col-md-12 bg-success img-div">
              <img src="https://images.pexels.com/photos/1374067/pexels-photo-1374067.jpeg?auto=compress&cs=tinysrgb&w=600&lazy=load" alt="" >
            </div>
            <div class="col-md-12 bg-success">
              <img src="https://images.pexels.com/photos/15186505/pexels-photo-15186505.jpeg?auto=compress&cs=tinysrgb&w=600&lazy=load" alt="" >
            </div> -->
      </VueSlickCarousel>
          </div>
        </div>
    </div>
  </template>

<script>
import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
// optional style for arrows & dots
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'

export default {
  name: 'SlickCarasoulComponent',
  components: { VueSlickCarousel },
  data(){
    return{
      settings:{
        "dots": true,
        arrows:true,
  // "focusOnSelect": true,
  // "infinite": true,
  // "speed": 500,
  "slidesToShow": 3,
  // "slidesToScroll": 3,
  // "touchThreshold": 5,
  autoplaySpeed:1000,
  speed:1000,
  "autoplay": true,
      }

}
  }
 
}

</script> 

<style scoped>
img{
  height: fit-content;
}
.img-div{
  height: 50vh;
}

</style>