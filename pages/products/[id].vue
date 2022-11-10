<template>
  <div>
    <h5>Product ID: {{ id }}</h5>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sapiente nobis
      quae libero eum exercitationem dolore sunt architecto pariatur provident
      voluptatum! Facilis vel laborum ad iusto? Natus quasi itaque commodi
      beatae!
    </p>
  </div>
</template>

<script setup>
const { id } = useRoute().params;
definePageMeta({
  layout: "products",
});
</script>

<style scoped></style>
