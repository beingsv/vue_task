<script setup lang="ts">

import AudioPlayer from "@swarmakit/vue/src/components/AudioPlayer/AudioPlayer.vue";
import Avatar from "@swarmakit/vue/src/components/Avatar/Avatar.vue";
</script>

<template>
  <div style="display: flex"><AudioPlayer src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3"></AudioPlayer>
    <Avatar/>
  </div>
</template>


<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
