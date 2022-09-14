<template>
  <div>
    <!-- <v-img src="/img/modern.png"></v-img> -->

    <v-card height="" flat class="ban1 d-flex align-center justify-content-center px-10 py-5">
      <v-row>
        <v-col cols="6" xs="12" sm="12" md="12" lg="6">
          <v-col cols="12" class="d-flex justify-start">
            <h1 class="white--text">Build stunning websites with</h1><br>
          </v-col>
          <v-col cols="12" class=" mt-0 d-flex justify-start">
            <h1 class="white--text">NuxtJs UI Kit</h1>
          </v-col>
          <v-col cols="12" class="d-flex justify-start">
            <p class="white--text">Free Vuetify UI Kit with Lots of Ready to Use Sections</p>
          </v-col>
          <v-col cols="12" class="d-flex justify-start">
            <div>
              <v-btn large class="pink white--text mr-4">download free</v-btn>
              <v-btn large outlined class="white--text">upgrade to pro</v-btn>
            </div>
          </v-col>
        </v-col>
        <v-col cols="6" xs="12" sm="12" md="12" lg="6">
          <v-img src='/banner1.png' height="500" width="500"></v-img>
        </v-col>
      </v-row>
    </v-card>

    <v-card flat class="features" height="450">
      <v-row class="pt-15">
        <v-col cols="12" class="d-flex justify-center">
          <h1 class="display-1">Banners</h1>
        </v-col>
      </v-row>
      <v-container>
        <v-container>

          <h4 class="grey--text text-center subtitle-1"> Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos,
            at
            aliquid doloremque inventore harum ut suscipit adipisci! Perferendis fugiat adipisci distinctio, accusamus
            autem
            non voluptatem consequatur deserunt itaque, delectus odio. </h4>
        </v-container>
      </v-container>
    </v-card>


    <v-card class="ban2 px-10 py-10" color=" d-flex align-center" center>
      <v-row>
        <v-col cols="6"  sm="12" md="6" lg="6">
          <v-col cols="12" class="d-flex justify-start">
            <v-chip color="black" class="white--text" small>Creating Brand</v-chip>
          </v-col>
          <v-col cols="12" class="d-flex justify-start">
            <v-row>
              <v-col cols="12" class="d-flex justify-start">
                <h1 class="white--text display-3">ONE BILLON PEOPLE</h1>
              </v-col>
              <v-col cols="12" class="d-flex justify-start">
                <h1 class="white--text display-3">USE FACEBOOK</h1>
              </v-col>
              <v-col cols="12" class="d-flex justify-start">
                <p class="text-start white--text">Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Laudantium
                  repellat eaque incidunt in dolor reprehenderit, corrupti repudiandae quibusdam. Dolorem nulla debitis
                  consectetur qui ab omnis in voluptatibus quod est vitae!</p>
              </v-col>
              <v-row>
                <v-col cols="12" class="d-flex justify-start">
                  <v-btn x-large rounded class="overline">Do you need help ?</v-btn>
                </v-col>
              </v-row>
            </v-row>
          </v-col>
        </v-col>
        <v-col cols="6" sm="12" md="6" lg="6" class="d-flex justify-content-center">
          <v-img src="/boy.png" width="300"></v-img>

        </v-col>
        <!-- <v-col cols="12" class="d-flex justify-start">
          <v-btn x-large rounded class="overline">Do you need help ?</v-btn>
        </v-col> -->
      </v-row>
    </v-card>

    <v-card flat height="600" class="d-flex align-center">
      <v-row>
        <v-col cols="12" class="d-flex justify-center">
          <h2> <span class="display-1 grey--text">I’m Johanthan Doe, </span> <span class="display-2">an
              Entreprenuer,</span></h2>
        </v-col>
        <v-col cols="12" class="d-flex justify-center">
          <h2><span class="display-2"> Designer & Front-end Developer</span>, <span
              class="display-1 grey--text">Making</span></h2>
        </v-col>

        <v-col cols="12" class="d-flex justify-center">
          <v-btn x-large class="pink" dark>check my work
            <v-icon dark small right>arrow_forward</v-icon>
          </v-btn>
        </v-col>
      </v-row>
    </v-card>

    <v-card class="ban3 d-flex align-center px-10" flat height="600">
      <v-row>
        <v-col cols="7">
          <v-row>
            <v-col cols="12">
              <h1 class="display-2">Give your Business</h1>
            </v-col>
            <v-col cols="12">
              <h1 class="display-2">Real boost Now!</h1>
            </v-col>
            <v-col cols="10">
              <p class="grey--text">To accomplish great things, we must not only act, but also dream; not only plan, but
                also believe.</p>
            </v-col>
          </v-row>
          <v-row>
            <v-col cols="7">
              <v-text-field placeholder="Enter Email Address" solo rounded></v-text-field>
              <v-btn class="primary" rounded large depressed>get start</v-btn>
            </v-col>
          </v-row>

        </v-col>
      </v-row>
    </v-card>



  </div>
</template>
<script>
  export default {
    data() {
      return {
        image: 'https://st.depositphotos.com/2208320/1860/v/450/depositphotos_18607965-stock-illustration-vector-model-face.jpg'
      }
    }
  }
</script>

<style scoped>
  .ban2 {
    background-color: rgb(253, 191, 168);
  }

  .ban1 {
    background-color: rgb(97, 124, 249);
  }

  .ban3 {
    background-color: rgb(233, 243, 248)
  }

  .ban4 {
    background-color: rgb(245, 248, 251)
  }
</style>back