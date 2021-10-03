<template lang="pug">
.container.py-6
  .flex.flex-row.items-center.justify-between
    .flex.flex-row.items-center
      img(alt="Boomba logo" src="../assets/logo.svg")
      .flex.flex-col.mx-8
        .title.font-semibold Boomba Bot
        .slogan The Discord bot made for streamers
    boomba-button Login
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import BoombaButton from './Button.vue';

@Options({
  name: 'boomba-navbar',
  components: {
    BoombaButton,
  },
})
export default class BoombaNavbar extends Vue {

}
</script>

<style lang="scss" scoped>
img {
  height: 52px;
}

.slogan {
  color: #CCC;
  font-size: 14px;
}

.title {
  font-size: 24px;
  font-family: "Comfortaa";
}
</style>
