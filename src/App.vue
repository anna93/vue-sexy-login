<template>
  <div id="app">
    <div class="container">
      <div class="blur-container"><div class="blur"></div></div>
      <div class="content">
        <div class="left">
          <h4 style="padding-top: 90px">Have an account?</h4>
          <p>Sign in your account</p>
          <button>Sign in</button>
        </div>
        <div class="right">
          <h4 style="padding-top: 90px">Don't have an account?</h4>
          <p>Sign up and build a better life</p>
          <button>Register</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss" src="./styles/style.scss"></style>
