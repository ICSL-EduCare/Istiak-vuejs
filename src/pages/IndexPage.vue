<template>
  <div class="q-pa-lg bg-grey-3">

    <div
      class="row q-col-gutter-lg justify-center"
      style="max-width: 1500px; margin: auto;"
    >

      <!-- LEFT SIDE : COVER PAGE -->
      <div class="col-12 col-md-5">

        <q-card class="cover-card q-pa-md">

          <div class="cover-image-area">

            <q-img
              :src="Image1"
              class="cover-image"
              fit="cover"
            />

            <!-- Black vertical title box -->
            <div class="black-box">

              <div class="portfolio-title">
                CREATIVE PORTFOLIO
              </div>

            </div>

          </div>

          <!-- Bottom Text -->
          <div class="row justify-between q-mt-md q-px-sm">

            <div class="text-caption">
              Design By:
              <br>
              <b>Istiak</b>
            </div>

            <div class="text-caption">
              2026
            </div>

          </div>

        </q-card>

      </div>


      <!-- RIGHT SIDE -->
      <div class="col-12 col-md-7">

        <div class="row q-col-gutter-md">

          <!-- PAGE 1 -->
          <div class="col-12 col-sm-4">

            <q-card class="page-card q-pa-md">

              <div class="text-h6 text-weight-bold">
                INDEX
              </div>

              <q-separator class="q-my-sm" />

              <div class="text-caption q-mb-xs">
                ABOUT THE DESIGN
              </div>

              <div class="text-caption q-mb-xs">
                TEAM
              </div>

              <div class="text-caption q-mb-xs">
                MODERN FASHION
              </div>

              <div class="text-caption q-mb-xs">
                NEW COLLECTION
              </div>

              <div class="text-caption q-mb-xs">
                INTERIORS
              </div>

              <q-img
                :src="Image1"
                class="small-image q-mt-md"
                fit="cover"
              />

            </q-card>

          </div>


          <!-- PAGE 2 -->
          <div class="col-12 col-sm-4">

            <q-card class="page-card q-pa-md">

              <div class="text-subtitle1 text-weight-bold">
                About The Studio
              </div>

              <div class="text-caption q-mt-sm">
                Creative portfolio and visual design studio.
                We create modern and minimal projects.
              </div>

              <q-img
                :src="Image1"
                class="medium-image q-mt-md"
                fit="cover"
              />

            </q-card>

          </div>


          <!-- PAGE 3 -->
          <div class="col-12 col-sm-4">

            <q-card class="page-card q-pa-md">

              <div class="text-subtitle1 text-weight-bold">
                Team
              </div>

              <div class="text-caption q-mt-sm">
                Creative Director
              </div>

              <q-img
                :src="Image1"
                class="team-image q-mt-md"
                fit="cover"
              />

              <div class="text-caption q-mt-sm">
                Photographer
              </div>

              <q-img
                :src="Image1"
                class="team-image q-mt-sm"
                fit="cover"
              />

            </q-card>

          </div>


          <!-- PAGE 4 -->
          <div class="col-12 col-sm-4">

            <q-card class="page-card q-pa-md">

              <div class="text-subtitle1 text-weight-bold">
                Modern Fashion Show
              </div>

              <q-img
                :src="Image1"
                class="large-image q-mt-md"
                fit="cover"
              />

              <div class="text-caption q-mt-md">
                Modern fashion focuses on clean design,
                simple colours and creative photography.
              </div>

            </q-card>

          </div>


          <!-- PAGE 5 -->
          <div class="col-12 col-sm-4">

            <q-card class="page-card q-pa-md">

              <div class="text-subtitle1 text-weight-bold">
                Modern Fashion
              </div>

              <div class="text-caption q-mt-sm">
                Contemporary visual concepts and creative styling.
              </div>

              <div class="row q-col-gutter-sm q-mt-sm">

                <div class="col-6">
                  <q-img
                    :src="Image1"
                    class="grid-image"
                    fit="cover"
                  />
                </div>

                <div class="col-6">
                  <q-img
                    :src="Image1"
                    class="grid-image"
                    fit="cover"
                  />
                </div>

              </div>

            </q-card>

          </div>


          <!-- PAGE 6 -->
          <div class="col-12 col-sm-4">

            <q-card class="page-card q-pa-md">

              <div class="text-subtitle1 text-weight-bold">
                New Collection
              </div>

              <div class="row q-col-gutter-sm q-mt-md">

                <div class="col-7">

                  <q-img
                    :src="Image1"
                    class="collection-image"
                    fit="cover"
                  />

                </div>

                <div class="col-5">

                  <div class="text-caption">
                    New creative collection combining photography,
                    fashion and minimal editorial design.
                  </div>

                </div>

              </div>

            </q-card>

          </div>


          <!-- PAGE 7 -->
          <div class="col-12 col-sm-6">

            <q-card class="page-card q-pa-md">

              <div class="text-subtitle1 text-weight-bold">
                Interiors
              </div>

              <div class="row q-col-gutter-sm q-mt-md">

                <div class="col-6">
                  <q-img
                    :src="Image1"
                    class="interior-image"
                    fit="cover"
                  />
                </div>

                <div class="col-6">
                  <q-img
                    :src="Image1"
                    class="interior-image"
                    fit="cover"
                  />
                </div>

              </div>

              <div class="text-caption q-mt-md">
                Clean, minimal and modern design concepts.
              </div>

            </q-card>

          </div>


          <!-- PAGE 8 -->
          <div class="col-12 col-sm-6">

            <q-card class="page-card q-pa-md">

              <div class="text-subtitle1 text-weight-bold">
                Best Collection
              </div>

              <div class="text-caption q-mt-sm">
                Selected projects from our latest creative works.
              </div>

              <div class="row q-col-gutter-sm q-mt-md">

                <div class="col-6">
                  <q-img
                    :src="Image1"
                    class="collection-small"
                    fit="cover"
                  />
                </div>

                <div class="col-6">
                  <q-img
                    :src="Image1"
                    class="collection-small"
                    fit="cover"
                  />
                </div>

              </div>

            </q-card>

          </div>

        </div>

      </div>

    </div>

  </div>
</template>


<script setup>
import Image1 from 'src/assets/Image1.png'
</script>


<style lang="sass" scoped>

.cover-card
  min-height: 720px
  background: white
  border-radius: 0

.cover-image-area
  height: 620px
  position: relative
  overflow: hidden

.cover-image
  width: 100%
  height: 100%

.black-box
  position: absolute
  left: 15px
  top: 15px
  bottom: 15px
  width: 130px
  background: #111
  display: flex
  align-items: center
  justify-content: center
  z-index: 2

.portfolio-title
  color: white
  font-size: 28px
  font-weight: 500
  letter-spacing: 3px
  writing-mode: vertical-rl
  transform: rotate(180deg)

.page-card
  min-height: 300px
  background: white
  border-radius: 0

.small-image
  height: 150px

.medium-image
  height: 170px

.team-image
  height: 90px

.large-image
  height: 170px

.grid-image
  height: 130px

.collection-image
  height: 170px

.interior-image
  height: 160px

.collection-small
  height: 150px

@media (max-width: 1023px)

  .cover-card
    min-height: auto

  .cover-image-area
    height: 600px

</style>