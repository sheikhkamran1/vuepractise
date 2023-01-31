<template>
  <template-view>
     <section>
       <div class="container">
        <card-component></card-component>
       </div>
     </section>
  </template-view>
</template>

<script>
import TemplateView from '@/views/TemplateView.vue'
import CardComponent from '@/components/CardComponentView.vue'
export default {
  components:{TemplateView,CardComponent}
}
</script>
