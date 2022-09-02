<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue';
</script>

<template>
  <div>
    <h1>GTM1040</h1>
  </div>

  <div>
    <form>
      <table>
        <tr>
          <td class="label">TCTO Status Code:</td>
          <td class="input-field"><input size="2" /></td>
        </tr>
        <tr>
          <td class="label">Description:</td>
          <td class="input-field"><input size="35" /></td>
        </tr>
        <tr>
          <td class="label">Start date:</td>
          <td class="input-field"><input size="2" /></td>
          <td><input size="3" /></td>
          <td><input size="4" /></td>
        </tr>
        <tr>
          <td class="label">Stop date:</td>
          <td class="input-field"><input size="2" /></td>
          <td><input size="3" /></td>
          <td><input size="4" /></td>
        </tr>
      </table>
      <input type="select" />
      <input type="submit" />
    </form>
  </div>

  <!--
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" />
  -->
</template>

<style scoped>
.input-field {
  text-align: left;
}
.label {
  font-style: bold;
  text-align: right;
}

.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
