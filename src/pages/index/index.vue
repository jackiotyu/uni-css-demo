<template>
    <view>
        <WithCss></WithCss>
    </view>
</template>

<script>
// 可以取消引入做对比
import WithCss from './WithCss.vue';
export default {
    components: { WithCss },
    data() {
        return {
            title: 'Hello',
        };
    },
    onLoad() {},
    methods: {},
};
</script>
