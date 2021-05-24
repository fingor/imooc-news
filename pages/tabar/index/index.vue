<template>
	<view class="content">
		<navbar></navbar>
		<view v-for="item in 100">
			{{item}}
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello123'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>


