<template>
  <div class="text-center mt-5 py-2" v-bind:style="`background-color: ${VUE_APP_FOOTER_BG_CSS_COLOR}; color: ${VUE_APP_FOOTER_TEXT_CSS_COLOR};`">
    <p class="m-0 p-0"><router-link :to="'/'" class="text-reset">EHDS v{{version}}</router-link> | Powered by <a href="https://github.com/yeikiu/vue-base-blog" target="_blank" class="text-reset">vue-base-blog</a></p>
    <p class="m-0 p-0">Created with ❤️ by <a href="https://github.com/yeikiu/" target="_blank" class="text-reset">JQ</a> © {{ new Date().toDateString().slice(-4) }}</p>
  </div>
</template>

<script language="ts">
import { version } from '@/../package.json'

const { VUE_APP_FOOTER_BG_CSS_COLOR = 'darkgray', VUE_APP_FOOTER_TEXT_CSS_COLOR = 'white' } = process.env

export default {
  data () {
    return {
      version,
      VUE_APP_FOOTER_BG_CSS_COLOR,
      VUE_APP_FOOTER_TEXT_CSS_COLOR
    }
  }
}
</script>
