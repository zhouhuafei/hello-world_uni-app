<template>
	<view class="g-wrap">
		<navigator class="g-guide" open-type="navigate" url="/pages/detail/index">
			<view>去详情页</view>
			<view class="iconfont icon-right"></view>
		</navigator>
		<g-test></g-test>
	</view>
</template>

<script>
	import gTest from '../../components/g-test';
	export default {
		data: {},
		components: {
			'g-test': gTest
		},
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
