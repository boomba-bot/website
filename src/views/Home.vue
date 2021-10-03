<template lang="pug">
.home
  boomba-navbar
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import BoombaNavbar from '../components/Navbar.vue';

@Options({
  components: {
    BoombaNavbar,
  },
})
export default class Home extends Vue {}
</script>
