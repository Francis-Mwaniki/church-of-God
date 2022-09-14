<template>
  <main>
    <!--   <Modal /> -->
    <VerticalNav />
    <WrittenSongs />
  </main>
</template>

<script>
import WrittenSongs from "../components/WrittenSongs.vue";
import VerticalNav from "../components/verticalNav.vue";
/* import Modal from "../components/modal.vue"; */
export default {
  components: { WrittenSongs, VerticalNav },
};
</script>

<style></style>
