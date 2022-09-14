<template>
  <div>
    <BannerCom></BannerCom>
    <featuers-view-vue></featuers-view-vue>
    <recent-work-vue></recent-work-vue>
  </div>
</template>

<script>
  import BannerCom from '../components/Banner_com.vue'
import featuersViewVue from '@/components/features/featuersView.vue'
  import recentWorkVue from '@/components/recentWork.vue'
  export default {
    name: 'Home-vue',

    components: {
      BannerCom,
   featuersViewVue,
      recentWorkVue
    },
  }
</script>