<template>
  <div class="q-pa-md flex flex-center full-height">

    <div class="row full-width" style="max-width: 1400px;">

      <div class="col-8">

        <q-card class="left-card">

          <div class="row items-center q-pa-md">

            <div class="logo q-mr-lg">
              <div class="text-purple q-gutter-md" style="font-size: 2em">
                <q-icon name="shopping_cart" color="red-5" size="40px" />
              </div>
            </div>

            <div class="row items-center q-gutter-md">

              <q-btn flat label="SERVICES" no-caps />
              <q-btn flat label="OFFICES" no-caps />
              <q-btn flat label="TEAM" no-caps />
              <q-btn flat label="PHILOSOPHY" no-caps />
              <q-btn flat label="SPACES" no-caps />

            </div>

          </div>


          <div class="image-area">

            <div class="circle"></div>

            <img
             :src="Image1"
             class="person-image"
            alt="Person"
          />

          </div>


          <div class="team">

            <div>OUR TEAM</div>

            <q-separator class="title-line" />

            <div class="name">
              Istiak Abedin
            </div>

            <div class="job">
              Machine Learning<br>
              Researcher
            </div>

            <a href="#">
              Explore
            </a>

          </div>

        </q-card>

      </div>


      <div class="col-4">

        <q-card class="right-card">

          <q-btn
            outline
            color="white"
            label="LOGIN"
            no-caps
            class="login-btn"
          />

          <div class="content">

            <div class="title">
              Your legal advisers
              <br>
              for the problems
              <br>
              of this century
            </div>

            <div class="subtitle">
              We offer solutions adapted to
              <br>
              today's needs
            </div>

            <q-btn
              color="white"
              text-color="primary"
              label="VIEW MORE"
              no-caps
              class="view-btn"
            />

          </div>

        </q-card>

      </div>

    </div>

  </div>
</template>


<script setup>
import { ref } from 'vue'
import Image1 from 'src/assets/Image1.png'

const tab = ref('offices')
</script>


<style lang="sass" scoped>

.left-card
  height: 770px
  position: relative

.right-card
  height: 770px
  background: #ff6266
  position: relative

.image-area
  position: absolute
  top: 150px
  left: 55%
  transform: translateX(-50%)
  width: 500px
  height: 480px

.circle
  width: 310px
  height: 310px
  background: #ff6266
  border-radius: 50%
  position: absolute
  left: 170px
  top: 70px
  z-index: 1

.person-image
  position: absolute
  width: 300px
  height: auto
  left: 180px
  top: 50px
  z-index: 2
  transform: scale(1.25)
  transform-origin: bottom center

.team
  position: absolute
  left: 40px
  top: 330px
  z-index: 3


.title-line
  width: 105px
  margin: 9px 0 20px
  background: #333333


.name
  margin-top: 15px
  color: grey


.job
  font-size: 20px
  margin: 8px 0 15px


.team a
  color: #ff6266


.login-btn
  position: absolute
  top: 30px
  right: 30px
  width: 105px
  height: 40px
  border-radius: 0 16px 0 16px


.view-btn
  width: 150px
  height: 48px
  border-radius: 0 22px 0 22px


.content
  position: absolute
  top: 170px
  left: 50px
  color: white


.title
  font-size: 30px
  font-weight: bold


.subtitle
  margin: 20px 0 35px

</style>