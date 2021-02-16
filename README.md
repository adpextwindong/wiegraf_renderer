# fftactics_fonter

Just a simple exercise in css text handling based on Final Fantasy's Dialog box. Its rendered using Vuejs.

Example:

App.vue:

```
<template>
  <div id="app">
    <fft_renderer
            name="Wiegraf Folles"
            msg="If the penalty for a crime is a fine, then that law only exists for the lower class."/>
  </div>
</template>

<script>
import fft_renderer from './components/fft_renderer.vue'

export default {
  name: 'App',
  components: {
    fft_renderer
  }
}
</script>
```
NOTE: The wiegraf png is hardcoded currently.

Here's a preview of what it looks like:

![](./readme_assets/preview.png)

I would like to work on this some more and integrate it with a THREEjs based game engine or something eventually.
Get it working on a set of dialog lines too. Maybe handle Japanese as well, who knows. This repo is mostly a reminder for a sideproject idea than anything else. If you're curious about anything just message me.

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
