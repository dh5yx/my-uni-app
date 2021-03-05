<template>
	<view>
<!-- 		<view class="">
			<text>小貂蝉</text>
		</view>
		<view class="">
			<text selectable space='ensp'>小 貂\n蝉</text>
		</view>

		<view class="box" hover-class="active" >
			<view class="box2" hover-class="active" hover-stop-propagation>
			</view>
		</view> -->
		
	<!-- 	<button type="primary">按钮</button>
		<button  type="warn">按钮</button>
		<button  type="warn" plain>按钮</button>
		<button  type="warn" plain disabled>按钮</button>
		<button  type="warn" plain :loading="true">按钮</button> -->
		
		<image src="../../static/logo.png" ></image>
		<image src="../../static/logo.png" mode='aspectFit' ></image>
	</view>
</template>

<script>
	export default {
		data() {
			return {

			}
		},
		methods: {

		}
	}
</script>

<style>
	.box {
		background-color: orange;
		height: 400px;
		width: 400px;
	}

	.box2 {
		background-color: #4CD964;
		height: 200px;
		width: 200px;
	}

	.active {
		background-color: deeppink;
	}
</style>
