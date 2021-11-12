<style>
* {
  margin: 0;
  padding: 0;
}

form {
  background: coral;
  height: 100vh;
  margin: 0px auto;
  padding: 50px;
}

input,
textarea {
  background: white;
  border: 0px solid;
  padding: 7px;
  margin: 8px auto;
  width: 300px;
  box-shadow: 0 0 3px #444;
  display: block;
  font-size: 13px;
}

button[type="submit"] {
  background: darkkhaki;
  padding: 12px;
  font-size: 15px;
  width: 200px;
  margin: 20px auto;
  display: block;
  border: none;
  box-shadow: 0 0 4px 2px #444;
  text-transform: uppercase;
  color: #3a3a34;
}
</style>

<template>
  <SendMail />
</template>

<script>
export default {};
</script>
