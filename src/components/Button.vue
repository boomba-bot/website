<template lang="pug">
button.flex.flex-row.px-4.py-2.rounded-lg
  slot
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'boomba-button',
});
</script>

<style scoped>
button {
  background: linear-gradient(104.73deg, #2A4057 0%, #4A2F4C 100%);
  font-family: "Comfortaa";
}
</style>
