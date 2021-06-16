<template>
<div class="container">
      <Header/>
  <img src="http://getwallpapers.com/wallpaper/full/a/5/d/544750.jpg" alt="Snow" style="width:100%;">
  
  <div class="centered"><h1>This is an about page</h1>
</div>
</div>
</template>
<script>
// @ is an alias to /src
import Header from '@/section/Header.vue'

export default {
  name: 'Home',
  components: {
    Header
  }
}
</script>