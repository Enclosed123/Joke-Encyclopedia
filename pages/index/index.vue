<template>
	<view>
		<view class="uni-list">
		<view class="uni-list-cell">
		<view class="uni-list-cell-navigate uni-navigate-right">
		列表一
		</view>
		</view>
		<view class="uni-list-cell" style="font-size: 16;">
		<view class="uni-list-cell-navigate uni-navigate-right">
		列表一
		</view>
		</view>
		<view class="uni-list-cell">
		<view class="uni-list-cell-navigate uni-navigate-right">
		列表一
		</view>
		</view>
		</view>
	</view>
	
	
</template>

<script>
	export default {
		data() {
			return {
				title: 'poi',
				lists: ['A', 'B', 'C', 'D', 'E']
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
</style>