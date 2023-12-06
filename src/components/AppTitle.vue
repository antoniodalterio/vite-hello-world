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
  text-align: center;
  font-size: 3.125rem;
  color: rgb(0, 184, 0);
}
</style>
