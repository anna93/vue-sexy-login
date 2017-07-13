<template>
  <transition name="right">
    <div class="router-view login">
      <br><br><br><b>{{msg}}</b>
    </div>
  </transition>
</template>

<script>
  export default {
    name: 'login',
    data() {
      return {
        msg: 'login form'
      };
    }
  };
</script>