<template>
  <section>
    <base-card>
      <h2>Page not Found</h2>
      <p>
        This Page could not be found - maybe check out all our
        <router-link to="/coaches">coaches</router-link>
      </p>
    </base-card>
  </section>
</template>

<script>
import BaseCard from '../components/ui/BaseCard.vue';
export default {
  components: { BaseCard },
};
</script>

<style></style>
