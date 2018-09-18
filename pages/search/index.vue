<template>
	<view class="g-wrap">
		<navigator class="g-guide" open-type="navigate" url="/pages/mine/index">
			<view>去个人中心页</view>
			<view class="iconfont icon-right"></view>
		</navigator>
	</view>
</template>

<script>
	export default {
		data: {},
		onLoad: function() {
			console.log('Search onLoad');
		},
		onShow: function() {
			console.log('Search onShow');
		},
		onHide: function() {
			console.log('Search onHide');
		}
	}
</script>

<style lang="scss"></style>
