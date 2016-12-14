<template>
	<p v-text='msg'></p>

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
<style scoped>
	p{
		font-size: 18px;
		color: red;
	}

</style>