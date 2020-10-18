<template>
  <div class="container">
    <Sidebar />
    <div class="content">
      <div class="real-content">
        <slot></slot>
      </div>
      <footer>Artistic director: Léo KADEM - Coding: Nadir KADEM</footer>
    </div>
  </div>
</template>

<style>
.container {
  margin: 0;
  min-height: 100vh;
  display: flex;
  justify-content: flex-start;
}
.content {
  flex-direction: column;
  display: flex;
  flex: 1;
  height: 100vh;
}
.real-content {
  padding: 16px;
  flex: 1;
}
footer {
  padding: 8px;
  background-color: rgba(255, 255, 255, 0.2);
  text-align: center;
  color: white;
}
</style>
