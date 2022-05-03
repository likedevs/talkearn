<template>
  <v-dialog
      v-model="dialog"
      max-width="1000"
  >
    <template v-slot:activator="{ on, attrs }">
      <p class="Paragraph-1 has-text is-white m-0"
         v-bind="attrs"
         v-on="on"
         @click.prevent="playVideo">
        Watch Explainer Video
      </p>
      <button class="video-play-btn"
              v-bind="attrs"
              v-on="on"
              @click.prevent="playVideo">
        <svg width="29" height="30" viewBox="0 0 29 30" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path
              d="M27.5182 12.257C29.3543 13.1342 29.4509 15.7096 27.6846 16.6951L5.29621 29.1869C3.66519 30.097 1.63638 28.9497 1.56618 27.0776L0.680851 3.46719C0.610653 1.5951 2.54895 0.328487 4.24447 1.13849L27.5182 12.257Z"
              fill="#2945FF"/>
        </svg>
      </button>
    </template>
    <v-card class="form-modal">
      <v-card-title class="text-h5">
        <span class="close-dialog theme--dark" @click="dialog = false" style="cursor: pointer">
          <v-icon class="theme--dark">mdi-close</v-icon>
        </span>
      </v-card-title>
      <v-card-text>
        <video id="video" ref="video" src="TET-Explainer-video-compressed-lower.mp4" controls playsinline>
        </video>
      </v-card-text>
    </v-card>
  </v-dialog>
</template>

<script>

import userApi from "~/api/userApi"
import {mapActions, mapGetters} from 'vuex'

export default {
  data() {
    return {
      dialog: false,
    }
  },
  computed: mapGetters({
    user: 'chat/getUser',
  }),
  watch: {
    dialog(newValue) {
      if (!newValue) {
        try {
          this.$refs.video.pause();
        } catch (e) {
          console.log(e);
        }
      }
    }
  },
  methods: {
    playVideo() {
      try {
        if (this.$refs.video === undefined) {
          setTimeout(() => {
            this.$refs.video.play();
          }, 1000);
        } else {
          this.$refs.video.play();
        }
      } catch (e) {
        console.log(e);
      }
    }
  }
}
</script>

<style scoped>

.form-modal {
  background-color: #FFF !important;
}

.form-modal .v-card__text {
  background-color: #FFF !important;
}

.close-dialog {
  width: 100%;
  text-align: right;
}

.text-h5 p {
  text-align: center;
  width: 79%;
  margin-top: -30px;
  margin-left: 10%;
}

video {
  width: 100%;
  height: 100%;
}

.v-dialog > .v-card > .v-card__text {
  padding: 0;
  margin-top: 0;
  background-color: #121217 !important;
}

.v-application .text-h5 {
  background-color: #121217;
}
</style>