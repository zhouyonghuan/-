<template>
	<view class="home">
		<view class="header">
			<view class="title">
				<text>乘客</text>
			</view>
		</view>
		<view class="main">
		</view>
		<view class="journey clearfix">
			<view class="journey_left">
				<text>附近行程</text>
			</view>
			<view class="journey_right">
				<text>全部</text>
				<image src="../../static/image/arrows1.png" mode=""></image>
			</view>
		</view>
		<view class="destination">	
		<view class="up" style="height: 144rpx;">
			<view class="up_left">
				<text>从</text>
				<input type="text" value="德智创业广场" />
				<text>到</text>
				<input type="text" value="西风工业园区" />
			</view>
			<view class="up_right">
				<text class="price">60</text>
				<text>元/人</text>
			</view>
		</view>
		<view class="bottom">
			<view class="bottom_left">
				
			</view>
		</view>
	</view>
 </view>
</template>

<script>
</script>
<style lang="scss">
	.clearfix:after {
	  content: ".";
	  display: block;
	  height: 0;
	  clear: both;
	  visibility: hidden;
	}
	.home{
		margin: 0rpx 24rpx;
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
			margin-bottom: 44rpx;
		}
		.journey{
			image{
				width: 12rpx;
				height: 20rpx;
			}
			.journey_left{
				float: left;
				text{
					font-size: 40rpx;
					font-weight: bold;
					line-height: 56rpx;
					color:rgba(0,0,0,1);
					opacity:1;
					font-family:PingFang SC;
					float: left;
				}
			}
			.journey_right{
				float: right;
				text{
					width:60rpx;
					height: 42rpx;
					font-family:PingFang SC;
					font-weight:500;
					line-height:42rpx;
					color:rgba(152,152,152,1);
					opacity:1;
					margin-right: 10rpx;
				}
			}
		}
		.destination{
			width:700rpx;
			height:310rpx;
			background:rgba(255,255,255,1);
			box-shadow:0px 3rpx 6rpx rgba(0,0,0,0.11);
			opacity:1;
			border-radius:24rpx;
			margin-top: 20rpx;
			.up_left{
				width: 264rpx;
				height: 104rpx;
				// border: 2rpx solid #007AFF;
				margin-top: 44rpx;
				margin-left: 31rpx;
				float: left;
				text{
					float: left;
					margin-right: 10rpx;
					font-size: 30rpx;
					// font-weight: bold;
					color: #8799A3;
				}
			}
			.up_right{
				width: 156rpx;
				height: 80rpx;
				float: right;
				margin-top: 64rpx;
				margin-right: 42rpx;
				.price{
					font-size: 80rpx;
					font-weight:bold;
					line-height: 42rpx;
					color:#F43F3B;
				}
				text{
					font-size: 60rpx;
					font-size: 28rpx;
					font-weight: bold;

				}
			}
		}
		.bottom_left{
			float: left;
			margin-left: -260rpx;
			width: 260rpx;
			height:100rpx;
			border: 1rpx solid;
			
		}
	}
	
</style>
