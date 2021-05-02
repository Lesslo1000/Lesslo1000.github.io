<template>
  <div class="container">
    <Sidebar />
    <div class="content" :style="{ backgroundImage: `url('${background}')` }">
      <div class="real-content">
        <slot></slot>
      </div>
      <footer>Artistic director: Léo KADEM - Coding: Nadir KADEM</footer>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    background: {
      type: String,
    },
  },
}
</script>

<style>
.error {
  margin-top: 15%;
  line-height: 2;
  text-align: center;
  color: white;
  align-self: center;
}

.container {
  min-height: 100vh;
  display: flex;
  justify-content: flex-start;
  margin: 0;
  padding: 0;
  height: 100vh;
  background-color: #12232e;
}
.content {
  flex-direction: column;
  display: flex;
  flex: 1;
  height: 100vh;
  background-size: cover;
}
.real-content {
  padding: 16px;
  flex: 1;
}
footer {
  padding: 8px;
  background-color: rgba(0, 0, 0, 0.4);
  text-align: center;
  color: white;
}
</style>
