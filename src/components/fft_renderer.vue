<template>
  <div class="fft_dialogue_box">
    <h1 v-if="first_line">{{ name }}</h1>
    <p class=fft_font> {{ msg }} </p>
    <img class=fft_thumb alt="Character Thumbnail" src="wiegraf.png">
  </div>
</template>

<script>
export default {
  name: 'fft_renderer',
  data : function() {
    return {
        first_line : false,
    }
  },
  props: {
    msg: String,
    name: String,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
/* Webfont CSS setup for Altima by Caveras */

@font-face {
  font-family: 'Altima';
    src: url('../assets/Altima.eot');
    src: url('../assets/Altima.eot?#iefix') format('embedded-opentype'),
         url('../assets/Altima.woff') format('woff'),
         url('../assets/Altima.ttf') format('truetype'),
         url('../assets/Altima.svg#Altima') format('svg');
  font-weight: normal;
  font-style: normal;
}

@media screen and (-webkit-min-device-pixel-ratio:0) {
  @font-face {
    font-family: 'Altima';
      src: url('../assets/Altima.svg') format('svg');
    font-weight: normal;
    font-style: normal;
  }
}

/* Style your elements with the code below */

.fft_font {
  font-family: 'Altima', sans-serif;
  float: left;
}

.fft_dialogue_box {
    background-image: url("../assets/dialog_box_texture.png");
}

.fft_dialogue_box {
    width: max-content;
    padding: 14px;
}
</style>
