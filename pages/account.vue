<template>
  <div>
    <h1>Mon compte</h1>
    <fieldset>
      <label for>
        Prénom
        <input id="name" type="text" />
      </label>
      <label for>
        Nom
        <input id="surname" type="text" />
      </label>
      <label for>
        Password
        <input type="password" />
      </label>
      <button>ok</button>
    </fieldset>
  </div>
</template>

<style scoped>
h1 {
  color: #fff;
}
fieldset {
  display: flex;
  flex-direction: column;
  background-color: rgba(255, 255, 255, 0.2);
  border: none;
  border-radius: 8px;
  padding: 16px;
  font-size: 20px;
  color: #fff;
}

label {
  margin-bottom: 8px;
}
button {
  border: none;
  display: inline-block;
  box-sizing: border-box;
  text-decoration: none;
  font-family: 'Roboto', sans-serif;
  text-transform: uppercase;
  font-weight: 400;
  color: #fff;
  background-color: #3369ff;
  box-shadow: inset 0 -0.6em 0 -0.35em rgba(0, 0, 0, 0.17);
  text-align: center;
  position: relative;
}
</style>
