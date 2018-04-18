<template>
  <div>
    <Login></Login>
  </div>
</template>
<script>
  import Login from './zhibo.vue'
  export default {
    data(){
      return{
      }
    },
    computed: {
    },
    watch:{
    },
    mounted(){
      document.title ="篮球直播"
    },
    methods: {
    },
    components:{
      Login,
    }
  }

</script>
<style>
  .ball{
    width: 100px;
    height: 100px;
    border-radius: 50px;
    background: red;
    animation:up 5s infinite;
    position: absolute;
  }
  @keyframes up {
    from {top:200px;transform:scale(0.1)}
    to {top:-200px;transform:scale(1)}
  }

</style>