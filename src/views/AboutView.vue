<template>
  <template-view>
    <div class="container">
      <div class="row py-5">
        <div class="col-md-12">
          <slick-carasoul-componenet></slick-carasoul-componenet>
        </div>
      </div>
    </div>
  </template-view>
</template>

<script>
import TemplateView from '@/views/TemplateView.vue'
import SlickCarasoulComponenet from '@/components/SlickCarasoulComponenet.vue';
export default {
  components:{TemplateView,SlickCarasoulComponenet}
}
</script>
