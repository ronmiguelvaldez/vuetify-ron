<template>
  <v-hover slot="{hover}">
    <v-card
    class="mx-auto mt-3" 
    color="black"
    max-width="600"
    >
    <v-img
    src="human.jpg"
    :aspect-ratio="16/9">

    <v-expand-transition>
        <div
        v-if="hover"
        class="d-flex transition-fast-in-fast-out blue darken-2 v-card--reveal text-h2 white--text"
        style="height: 100%;">
        Ron Miguel Valdez
        </div>
    </v-expand-transition>
    </v-img>
    <v-card-text class="pt-6" style="position: relative;">
        <v-btn
        absolute
        color="blue"
        class="white--text"
        fab
        medium
        right
        top>
        <v-icon> mdi-information</v-icon>
        </v-btn>

        <div class="font-weight-light white--text text-h6 mb-2"> 
            A man standing
            <h3 class="font-weight-light text-h4 mb-2">
                Dark Tone Solemn
            </h3>
            <div class="font-weight-light text-h6 mb-2 grey--text">
                Finding inner peace in a world full of darkness
            </div>
        </div>

    </v-card-text>
    </v-card>
  </v-hover>
</template>

<script>
export default {

}
</script>

<style>
.v-card--reveal {
  align-items: center;
  bottom: 0;
  justify-content: center;
  opacity: .5;
  position: absolute;
  width: 100%;
}
</style>