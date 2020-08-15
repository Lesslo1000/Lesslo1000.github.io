<template>
  <div class="logo">
    <span>L</span>
  </div>
</template>

<style>
.logo {
  color: #fff;
  border: 8px solid white;
  font-size: 100px;
  font-weight: bold;
  width: 120px;
  height: 120px;
  border-radius: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  background: linear-gradient(
    135deg,
    rgba(232, 153, 202, 1) 0%,
    rgba(207, 17, 153, 1) 100%
  );
  box-shadow: 8px 8px 8px 2px rgba(0, 0, 0, 0.23);
  margin-bottom: 24px;
  align-self: center;
}

.logo span {
  transition: transform 1s ease-in-out;
}

.logo:hover span {
  transform: rotate(360deg);
}

@media only screen and (max-width: 600px) {
  .logo {
    width: 40px;
    height: 40px;
    font-size: 24px;
  }
}
</style>
