<template>
  <transition name="right">
    <div class="router-view login">
      <br><br><br><b>{{msg}}</b>
      <br><headersam></headersam>
    </div>
  </transition>
</template>

<script>
  import headersam from '../../components/headersam.vue';

  export default {
    name: 'login',
    components: {
      headersam
    },
    data() {
      return {
        msg: 'login form'
      };
    }
  };
</script>