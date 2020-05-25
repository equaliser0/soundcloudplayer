<template>
  <SoundCloud
    playlist="936742843"
    :mini="false"
  /></template>

<script>
import SoundCloud from 'vue-soundcloud-player';

export default {
  name: 'player',
  components: {
    SoundCloud
  }
}
</script>
