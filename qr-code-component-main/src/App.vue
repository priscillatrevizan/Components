<script setup>
import QrCode from './components/QrCode.vue';
</script>

<template>
  <main>
    <QrCode />
    <footer class="attribution">
      <p>Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>.</p>
      <p>Coded by <a href="https://github.com/priscillatrevizan" target="_blank">Priscilla Trevizan</a>.</p>
    </footer>
  </main>

</template>

<style scoped>
#app {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
}

.attribution {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin: 0;
  margin-top: 25px;
  padding: 0;
  font-family: var(--font-family);
}

.attribution a {
  text-decoration: none;
  color: var(--color-slate-900);
  font-weight: var(--font-weight-bold);
  margin: 0;
  padding: 0;
}

.attribution p {
  margin-top: 4px;
  box-sizing: border-box;
}
</style>
