<template>
    <div>
        <v-card flat class="features" height="270">
                <v-row class="pt-15">
                    <v-col cols="12" class="d-flex justify-center">
                        <h1 class="display-1">Features</h1>
                    </v-col>
                </v-row>
                <h4 class="grey--text text-center subtitle-1">Here you can check Demos we created you can easily use it.
                    Its quite easy to Create </h4>
                <h4 class="grey--text text-center subtitle-1">your own dream website & dashboard in No-time</h4>
        </v-card>

        <feature-one-vue></feature-one-vue>
        <feature-two-vue></feature-two-vue>

    </div>
</template>


<script>
    import featureOneVue from './featureOne.vue';
    import featureTwoVue from './featureTwo.vue';
export default {
 components:{
    featureOneVue,
    featureTwoVue
 }   
}
</script>

<style scoped>

  .features{
    background-color: rgb(245,249,250)
  }
</style>