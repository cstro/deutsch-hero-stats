<template>
  <div>
    <h2>{{ hero.name }}</h2>

    <div>Dexterity: {{ hero.dexterity }}</div>
  </div>
</template>

<script>
export default {
  name: 'HeroProfile',
  props: {
    hero: {
      type: Object,
      required: true,
    }
  }
}
</script>