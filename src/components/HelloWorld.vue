<template>
  <div>
    <a href="url">直播</a>
  </div>

</template>
<script>
  import qs from 'qs';
  export default{
    data(){
      return {
        url:''
      }
    },
    mounted(){
      //处理加载完毕后的事件
      this.getUrl()
    },
    methods: {

      getUrl:function () {
        var _this = this;
        fetch('/video/play_address?device_id=29493653&channel_id=1&protocol_type=1&pack=1',{
          method:'GET',
          headers: new Headers({
            "api-key":"wv=duRwVtU3IPsM=lzY9C2V7AVQ="
          })
        }).then(function(response) {
            _this.url = response.data.playaddr
        }).catch(function(err) {

        });
      },

    }
  }
</script>
<style>
</style>