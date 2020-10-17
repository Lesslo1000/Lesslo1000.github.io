<template>
  <div class="container">
    <Sidebar />
    <div class="content">
      <div class="page">
        <Nuxt />
      </div>
      <footer>Artistic director: Léo KADEM - Coding: Nadir KADEM</footer>
    </div>
  </div>
</template>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

.container {
  display: flex;
  flex-direction: row;
  font-size: 16px;
  margin: 0;
  padding: 0;
  height: 100vh;
  align-items: stretch;
  background-color: #12232e;
}

.page {
  overflow: auto;
  flex: 1;
}

.content {
  flex-direction: column;
  display: flex;
  flex: 1;
  height: 100vh;
}

footer {
  padding: 8px;
  background-color: rgba(255, 255, 255, 0.2);
  text-align: center;
  color: white;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}
</style>
