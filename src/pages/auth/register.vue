<template>
  <transition name="left">
    <div class="router-view register">
      <br><br><br><b>{{msg}}</b>
      <br>
      <headersam></headersam>
    </div>
  </transition>
</template>

<script>
  import headersam from '../../components/headersam.vue';
  
  export default {
    name: 'register',
    components: {
      headersam
    },
    data() {
      return {
        msg: 'register form'
      };
    }
  };
</script>