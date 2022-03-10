<template>
  <section>
    <h4>Oops! There ws an error:</h4>
    <p>{{ error }}</p>
  </section>
</template>

<script>
export default {
  props: ['error']
}
</script>
