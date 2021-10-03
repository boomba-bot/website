<template lang="pug">
button.flex.flex-row.px-4.py-2.rounded-lg
  slot
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';

@Options({
  name: 'boomba-button',
})
export default class BoombaButton extends Vue {

}
</script>

<style scoped>
button {
  background: linear-gradient(104.73deg, #2A4057 0%, #4A2F4C 100%);
  font-family: "Comfortaa";
}
</style>
