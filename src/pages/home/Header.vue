<template>
	<header class= "header">
		<a class= "header-left"><span class = "iconfont icon-left-angle"></span></a>
		<div class= "header-title" >输入城市/景点/游玩主题</div>
		<div class= "header-right">
			<span class= "nav-city">北京</span>
			<span class= "triangle-down "></span>
		</div>
	</header>
</template>

<script>

	export default {
		
	}

</script>

<style scoped>
	.header {
	    position: relative;
	    width: 100%;
	    height: .88rem;
	    background: #00bcd4;
	    text-align: center;
	    color: #fff;
	}
	.header-left {
		float: left;
	    width: .4rem;
	    line-height: .88rem;
	    padding: 0 .2rem;
	    font-size: .36rem;
	    text-align: left;
	    color: #fff;
	}
	.header-title {
	    position: absolute;
	    top: .14rem;
	    left: .8rem;
	    right: 1.28rem;
	    line-height: .6rem;
	    background: #fff;
	    color: #ccc;
	    border-radius: .06rem;
	}
	.header-right {
		float: right;
		width: 1.28rem;
		line-height: .88rem;
	}
	.nav-city{
		position :absolute;
		right:.5rem;
	}
	.triangle-down {
	    width: 0;
	    height: 0;
	    border-left: .1rem solid transparent;
	    border-right: .1rem solid transparent;
	    border-top: .1rem solid #fff;
		position: absolute;
		top :.4rem;
		right :.2rem;
	}
</style>
