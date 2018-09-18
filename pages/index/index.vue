<template>
	<view class="g-wrap">
		<navigator class="g-guide" open-type="navigate" url="/pages/detail/index">
			<view>去详情页</view>
			<view class="iconfont icon-right"></view>			
		</navigator>
	</view>
</template>

<script>
	export default {
		data: {},
		onLoad: function() {
			console.log('Index onLoad');
		},
		onShow: function() {
			console.log('Index onShow');
		},
		onHide: function() {
			console.log('Index onHide');
		}
	}
</script>

<style lang="scss"></style>
