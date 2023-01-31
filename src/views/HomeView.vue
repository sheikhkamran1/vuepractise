<template>
   <template-view>
         <div id="carouselExample" class="carousel slide">
         <div class="carousel-inner">
            <div class="carousel-item active">
               <img src="https://cdn.pixabay.com/photo/2023/01/14/13/17/bellflower-7718193__340.jpg" class="d-block w-100" alt="...">
            </div>
            <div class="carousel-item">
               <img src="https://cdn.pixabay.com/photo/2023/01/14/10/18/buildings-7717853__340.jpg" class="d-block w-100" alt="...">
            </div>
            <div class="carousel-item">
               <img src="https://cdn.pixabay.com/vimeo/778907198/Christmas%20-%20141964.mp4?width=640&hash=85c931219de800ff2e651bf0e82b092b6f6cc1f4" class="d-block w-100" alt="...">
            </div>
         </div>
         <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
         </button>
         <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
         </button>
         </div>
   </template-view>
</template>

<script>
import TemplateView from '@/views/TemplateView.vue'
export default {
   components:{TemplateView}
}
</script>

<style scoped>
/* .carousel{
   width: 100%;
   height: 60vh;
} */
.carousel-item{
   height: 400px;
   width: 100%;
}
</style>
