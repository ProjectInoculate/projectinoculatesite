<template>
  <div class="login-window">
    <div class="login-window__inner">
      <input
        type="text"
        placeholder="Username"
        v-model="UserCreate">
      <input
        type="password"
        placeholder="Password"
        v-model="UserCreate">
    </div>
  </div>
</template>

<script>
export default {
  name: 'PILogin',
  methods: {
    UserCreate () {
      // Some Stuff
    }
  }
}
</script>


<style lang="scss">
.login-window {
  background-color: tomato;
  padding: 20px 0px;
  width: 85%;
  &__inner {
    width: 85%;
    margin: 0px auto;
  }
}
</style>

