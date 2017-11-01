<template>
	<div>
		<index-header/>  
		<index-banner/>
	</div>
</template>

<script>
	import header from "./header.vue"; // 引入组件时候 要定义一个组件
	import banner from "./banner.vue"
	export default {
		components: {
			"index-header": header ,//定义一个组件
			"index-banner": banner
		} 
	}
</script>

<style scoped>
	
</style>