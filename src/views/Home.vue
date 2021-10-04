<template lang="pug">
.home
  boomba-navbar
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import BoombaNavbar from '../components/Navbar.vue';

export default defineComponent({
  name: 'Home',
  components: {
    BoombaNavbar,
  },
});
</script>
