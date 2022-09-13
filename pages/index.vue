<template>
  <!-- <div>
    <p>Icons</p>
    <font-awesome-icon :icon="['fab', 'linkedin']" />
    <font-awesome-icon :icon="['fab', 'github']" />
    <font-awesome-icon :icon="['fab', 'facebook']" />
    <font-awesome-icon :icon="['fas', 'coffee']" />
  </div> -->

  <main><Hero /></main>
</template>

<script>
import Hero from '../components/Hero.vue'
export default {
  name: 'IndexPage',
  components: { Hero },
}
</script>
