<template>
  <v-container class="my-15">
    <v-row
      class="px-3 d-flex flex-column flex-md-row justify-center justify-md-space-between align-center"
    >
      <v-col cols="8" md="4" class="pa-0 d-flex flex-column align-center">
        <v-col class="pa-0"
          ><div class="heading text">
            10,000+ of our users love our products.
          </div></v-col
        >

        <v-col cols="10" sm="12" class="pa-0 mt-4"
          ><div class="para text">
            We only provide great products combined with excellent customer
            service. See what our satisfied customers are saying about our
            services.
          </div></v-col
        >
        <v-spacer></v-spacer>
      </v-col>

      <v-col cols="8" md="6" class="mt-6 pa-0">
        <v-col cols="12" class="d-flex pa-0 mb-3">
          <v-sheet
            rounded
            class="label d-flex flex-column flex-sm-row align-center pl-5 justify-center"
          >
            <div class="my-2">
              <v-icon icon="mdi-star" start class="star"></v-icon>
              <v-icon icon="mdi-star" start class="star"></v-icon>
              <v-icon icon="mdi-star" start class="star"></v-icon>
              <v-icon icon="mdi-star" start class="star"></v-icon>
              <v-icon icon="mdi-star" start class="star mr-5"></v-icon>
            </div>
            <div class="label-text">Rated 5 Stars in Reviews</div>
          </v-sheet>
        </v-col>

        <v-col cols="12" class="d-flex justify-center pa-0 mb-3">
          <v-sheet
            rounded
            class="label d-flex flex-column flex-sm-row align-center pl-5 justif-center"
          >
            <div class="my-2">
              <v-icon icon="mdi-star" start class="star"></v-icon>
              <v-icon icon="mdi-star" start class="star"></v-icon>
              <v-icon icon="mdi-star" start class="star"></v-icon>
              <v-icon icon="mdi-star" start class="star"></v-icon>
              <v-icon icon="mdi-star" start class="star mr-5"></v-icon>
            </div>
            <div class="label-text">Rated 5 Stars in Report Guru</div>
          </v-sheet>
        </v-col>

        <v-col cols="12" class="d-flex pa-0 justify-end">
          <v-sheet
            rounded
            class="label d-flex flex-column flex-sm-row align-center pl-5 justif-center"
          >
            <div class="my-2">
              <v-icon icon="mdi-star" start class="star"></v-icon>
              <v-icon icon="mdi-star" start class="star"></v-icon>
              <v-icon icon="mdi-star" start class="star"></v-icon>
              <v-icon icon="mdi-star" start class="star"></v-icon>
              <v-icon icon="mdi-star" start class="star mr-5"></v-icon>
            </div>
            <div class="label-text">Rated 5 Stars in BestTech</div>
          </v-sheet>
        </v-col>
      </v-col>
    </v-row>
    <v-row class="main-row mt-15 d-flex justify-center pa-0">
      <v-col
        cols="8"
        sm="5"
        md="4"
        class="d-flex flex-column "
        align-self="start"
      >
        <div class="card pa-5">
          <div class="d-flex">
            <v-col cols="3" class="pa-0"
              ><v-avatar>
                <v-img
                  alt=""
                  src="/src/assets/image-colton.jpg"
                ></v-img> </v-avatar
            ></v-col>
            <v-col cols="9" class="pa-0">
              <div class="data d-flex flex-column">
                <div class="name">Colton Smith</div>
                <div class="position">Verified Buyer</div>
              </div>
            </v-col>
          </div>
          <div>
            <v-col class="card-text">
              "We needed the same printed design as the one we had ordered a
              week prior. Not only did they find the original order, but we also
              received it in time. Excellent!"
            </v-col>
          </div>
        </div>
      </v-col>

      <v-col
        cols="8"
        sm="5"
        md="4"
        class="d-flex flex-column"
        align-self="center"
      >
        <div class="card pa-5">
          <div class="d-flex">
            <v-col cols="3" class="pa-0"
              ><v-avatar>
                <v-img
                  alt=""
                  src="/src/assets/image-irene.jpg"
                ></v-img> </v-avatar
            ></v-col>
            <v-col cols="9" class="pa-0">
              <div class="data d-flex flex-column">
                <div class="name">Irene Roberts</div>
                <div class="position">Verified Buyer</div>
              </div>
            </v-col>
          </div>
          <div>
            <v-col class="card-text">
              "Customer service is always excellent and very quick turn around.
              Completely delighted with the simplicity of the purchase and the
              speed of delivery."
            </v-col>
          </div>
        </div>
      </v-col>

      <v-col cols="8" sm="5" md="4" class="d-flex flex-column" align-self="end">
        <div class="card pa-5">
          <div class="d-flex">
            <v-col cols="3" class="pa-0"
              ><v-avatar>
                <v-img
                  alt=""
                  src="/src/assets/image-anne.jpg"
                ></v-img> </v-avatar
            ></v-col>
            <v-col cols="9" class="pa-0">
              <div class="data d-flex flex-column">
                <div class="name">Anne Wallace</div>
                <div class="position">Verified Buyer</div>
              </div>
            </v-col>
          </div>
          <div>
            <v-col class="card-text">
              "Put an order with this company and can only praise them for the
              very high standard. Will definitely use them again and recommend
              them to everyone! "
            </v-col>
          </div>
        </div>
      </v-col>
    </v-row>
  </v-container>
</template>

<script setup>
</script>

<style scoped>
@font-face {
  font-family: f1;
  src: url(/src/assets/LeagueSpartan-Bold.ttf);
}
.main-row {
  height: 250px;
}
.text {
  color: hsl(301, 45%, 22%);
}
.heading {
  font-size: 40px;
  font-weight: 1000;
  font-family: f1;
  line-height: 1;
}
.para {
  font-size: 13px;
  color: hsl(317, 24%, 32%);
}
.label {
  background-color: hsl(300, 24%, 96%);
  font-size: 10px;
  font-weight: 400;
  height: 40px;
  width: 334px;
}
.star {
  color: hsl(28, 80%, 60%);
  margin-right: 3px; /* Adjust this value to control space between stars */
  padding: 0; /* Ensures no padding is added */
}
.label-text {
  font-size: 12px;
  color: hsl(301, 45%, 22%);
  font-weight: bold;
}
.card {
  width: 100%;
  height: 100%;
  background-color: hsl(301, 45%, 22%);
  border-radius: 5px;
}
.card-text {
  font-size: 12px;
  color: white;
}
.name {
  font-size: 12px;
  color: white;
}
.position {
  font-size: 12px;
  color: hsl(333, 80%, 67%);
}

@media screen and (max-width: 959.5px) {
  .main-row {
    height: 400px; /* Adjust to your desired height */
  }
  .heading,
  .para {
    text-align: center;
  }
}

@media screen and (max-width: 618.5px) {
  .main-row {
    height: 450px; /* Adjust to your desired height */
  }
  .heading,
  .para {
    text-align: center;
  }
}

@media screen and (max-width: 599.5px) {
  .main-row {
    height: 550px; /* Adjust to your desired height */
  }
  .heading,
  .para {
    text-align: center;
  }
  .label {
    height: 60px;
  }
}
</style>