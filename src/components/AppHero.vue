<script>
export default {
  name: 'jumbo',
  data() {
    return {
      description: 'Ciao sono Antonio, sto usando per la prima volta Vite',
    };
  },
};
</script>
<template>
  <div class="jumbo">
    <p>{{ description }}</p>
    <p>Alunno della Classe 110 di Boolean</p>
  </div>
</template>

<style scope>
.jumbo {
  width: 50%;
  background-color: rgb(48, 48, 214);
  margin: 50px auto;
  text-align: center;
  height: 200px;
  border-radius: 10px;
}

p {
  font-size: 25px;
  color: rgb(0, 184, 0);
  font-weight: bolder;
}
</style>
