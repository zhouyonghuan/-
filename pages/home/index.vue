<template>
	<view class="home">
		<view class="header">
			<view class="title">
				<text>乘客</text>
			</view>
		</view>
		<view class="main">
			<form>
				<view class="cu-form-group margin-top">
					<view class="title">邮件</view>
					<input placeholder="两字短标题" name="input"></input>
				</view>
			</form>
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
		.main{
			width:350*2rpx;
			height:248*2rpx;
			background:rgba(242,242,242,1);
			box-shadow:0rpx 3*2rpx 8*2rpx rgba(0,0,0,0.1);
			opacity:1;
			border-radius:18*2rpx;
			margin-left: 24rpx;
			margin-right: 24rpx;
		}
	}
</style>
