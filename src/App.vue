<template>
<div class="row">

<div class="col-md-6">

  <Nav />
  <Chat />
</div>
<div class="col-md-6 text-danger pl-5" style="z-index:99;top:30vh;left:10%">
  <img src="./assets/logo.png" alt="">
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
