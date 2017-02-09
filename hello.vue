<template>
	<p class='hello' v-text='msg'></p>

</template>

<script >
	module.exports={

		  data:function(){
		  	  return {
		  	  	  msg:'你好',
		  	  }
		  },


	}

</script>
<style scoped lang='less'>
	p{
		font-size: 18px;
		/*color: red;*/
	}
	@hello: green;
@world: #66bb33;

  .hello {
color: @hello;
  }

</style>