<script>
export default {
  name: 'titolo',
  data() {
    return {
      title: 'La mia prima app con Vite',
    };
  },
};
</script>
<template>
  <h1>{{ title }}</h1>
</template>

<style scope>
h1 {
  font-size: 3.125rem;
}
</style>
