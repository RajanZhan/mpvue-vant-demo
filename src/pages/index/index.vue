<template>
  <div class="" >

	<van-button @click="clickHandle" type="warning">vant 按钮组件 </van-button>
	
  </div>
</template>

<script>
import Toast from '@/../static/vant/toast/toast';
export default {
  data () {
    return {
      motto: 'Hello World',
      userInfo: {}
    }
  },

  components: {

  },


  methods: {
 
    clickHandle () {;
		console.log("toast is ",Toast);
		
		Toast.success('成功文案');
		console.log('clickHandle:', msg, ev)
    }
  },
}
</script>
