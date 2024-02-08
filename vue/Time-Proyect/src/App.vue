<template>
  <div>
    <header>
      <button class="menu-button" @click="goBack"> Inicio </button>
      <button class="menu-button-cs" @click="logout"> Cerrar Sesion </button>
    </header>
    <div class="grid-container">
      <div class="area area1">Area 1</div>
      <div class="area area2">Area 2</div>
      <div class="area area3">Area 3</div>
      <div class="area area4">Area 4</div>
      <div class="area area5">Area 5</div>
      <div class="area area6">Area 6</div>
      <div class="area area7">Area 7</div>
      <div class="area area8">Area 8</div>
      <div class="area area9">Area 9</div>
      <div class="area area10">Area 10</div>
      <div class="area area11">Area 11</div>
      <div class="area area12">Area 12</div>
      <div class="area area13">Area 13</div>
    </div>
    <footer class="footer">
      <p>Calendario</p>
    </footer>
  </div>
</template>


<style scoped>
@import './assets/grid.css';
@import './assets/menu.css';
@import './assets/footer.css';
</style>

<script>
export default {
  methods: {
    goBack() {
      this.$router.push('/App.vue');
    },
    logout() {
      // Lógica para cerrar sesión
    }
  }
}
</script>