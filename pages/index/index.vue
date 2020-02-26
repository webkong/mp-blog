<template>
	<view><web-view src="https://blog.webkong.cn"></web-view></view>
</template>

<script>
export default {
	data() {
		return {
		};
	},
	onLoad() {},
	methods: {},
	onShareAppMessage(res) {
		return {
			title: 'WebKong的网络日志',
			path: '/pages/index/index',
			imageUrl: 'https://blog.webkong.cn/images/common/head.jpg'
		};
	}
};
</script>

<style></style>
