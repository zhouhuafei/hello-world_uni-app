<template>
    <view class="g-wrap">
        <navigator class="g-guide" open-type="navigate" url="/pages/search/index">
            <view>去搜索页</view>
            <view class="iconfont icon-right"></view>
        </navigator>
    </view>
</template>

<script>
    export default {
        data: {},
        onLoad: function () {
            console.log('Detail onLoad');
        },
        onShow: function () {
            console.log('Detail onShow');
        },
        onHide: function () {
            console.log('Detail onHide');
        },
    };
</script>

<style lang="scss"></style>
