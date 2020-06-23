<template>
	<view class="home">
		<view class="header">
			<view class="title">
				<text>乘客</text>
			</view>
		</view>
		<view class="main">
			<view class="input1">
				<input type="text" value="" placeholder="我的位置"/>
			</view>
			<view class="inpu2">
				<input type="text" value="" placeholder="你要去哪儿" />
			</view>
		</view>
	</view>
</template>

<script>
</script>
<style lang="scss">
	.home{
		.header{
			display: flex;
			justify-content: center;
			margin-bottom: 20rpx;
			text {
				font-size: 26rpx;
			}
		}
	}
	.main{
		width: 700rpx;
		height: 496rpx;
		border-radius: 30rpx;
		background:rgba(242,242,242,1);
		margin: auto;
		margin-bottom: 44rpx;
		.input1{
			width: 100rpx;
			height: 100rpx;
			border: 1rpx solid #007AFF;
		}
	}
</style>
