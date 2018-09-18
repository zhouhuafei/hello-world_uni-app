<script>
	export default {
		onLaunch: function() {
			console.log('App onLaunch');
		},
		onShow: function() {
			console.log('App onShow');
		},
		onHide: function() {
			console.log('App onHide');
		}
	};
</script>

<style lang="scss">
	/* 
	每个页面公共css
	uni-app默认使用flex布局。因为flex布局有利于跨更多平台，尤其是采用原生渲染的平台。如不了解flex布局，请参考http://www.w3.org/TR/css3-flexbox/。若不需要flex布局可删除本行
	*/
	/*
    page,
    view {
        display: flex;
	}

    page {
        min-height: 100%;
    }
	*/
	/* 以上是uni-app默认自带的样式，本人由于用不习惯全部都是flex，所以干掉了。 */

	@import './scss/iconfont.scss';

	page {
		font-family: "iconfont";
		line-height: 1;
	}

	.g-guide {
		display: flex;
		align-items: center;
	}
</style>
