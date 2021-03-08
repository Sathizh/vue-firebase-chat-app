<template>
<div class="row">

<div class="col-md-6">

  <Nav />
  <Chat />
</div>
<div class="col-md-6 pl-5" style="z-index:99;top:30vh;left:10%">
  <img src="./assets/logo.png" alt="">
  <h2 class="pl-5">Dveloped by Me : )</h2>
</div>
</div>
</template>

<script>
import Nav from '@/components/Nav.vue'
import Chat from '@/components/Chat.vue'

export default {
  name: 'App',
  components: { Nav, Chat }
}
</script>
