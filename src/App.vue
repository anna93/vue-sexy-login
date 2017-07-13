<template>
  <div id="app">
    <div class="container">
      <div class="blur"></div>
      <div class="content">
        <div class="left">
          <h4 style="padding-top: 90px">Already have an account?</h4>
          <p>Sign in to your account</p>
          <router-link to="/login">Sign in</router-link>
        </div>
        <div class="right">
          <h4 style="padding-top: 90px">Don't have an account?</h4>
          <p>Register now! and build a better life</p>
          <router-link to="/register">Register</router-link>
        </div>
      </div>
      <router-view></router-view>
    </div>
  </div>
</template>

<script>
import axios from 'axios';

export default {
  name: 'app',
  mounted() {
    axios.get('https://www.google.co.in')
      .then(res => {
        console.warn(res.data);
      })
      .catch(err => {
        console.warn(err);
      });
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    };
  }
};
</script>

<style lang="scss" src="./styles/style.scss"></style>
