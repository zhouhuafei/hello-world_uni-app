<template>
	<view class="g-wrap">
		<navigator class="g-guide" open-type="navigate" url="/pages/index/index">
			<view>去首页</view>
			<view class="iconfont icon-right"></view>
		</navigator>
	</view>
</template>

<script>
	export default {
		data: {},
		onLoad: function() {
			console.log('Mine onLoad');
		},
		onShow: function() {
			console.log('Mine onShow');
		},
		onHide: function() {
			console.log('Mine onHide');
		}
	}
</script>

<style lang="scss"></style>
