<template>
  <div>
    <h1>Deutsch Hero Stats</h1>
    <hero-profile />
  </div>
</template>

<script>
import HeroProfile from '~/components/HeroProfile'

export default {
  components: {
    HeroProfile,
  },
  data() {
    return {
      heroChris: {
        name: 'Chris',
        dexterity: 1,
      },
    }
  }
}
</script>
