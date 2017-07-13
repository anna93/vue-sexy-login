<template>
  <transition name="left">
    <div class="router-view register">
      <br><br><br><b>{{msg}}</b>
    </div>
  </transition>
</template>

<script>
  export default {
    name: 'register',
    data() {
      return {
        msg: 'register form'
      };
    }
  };
</script>