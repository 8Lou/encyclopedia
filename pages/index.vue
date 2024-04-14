<template>
  <div>
    <Main />
    <ul>
      <li><nuxt-link to="/sql">SQL</nuxt-link></li>
      <li><nuxt-link to="/api">API</nuxt-link></li>
      <li><nuxt-link to="/logs">Logs</nuxt-link></li>
    </ul>
  </div>
</template>

<script>
import Main from "../components/Main.vue";

export default {
  components: {
    Main,
  },
};
</script>
