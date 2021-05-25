<template>
	<view>
		<scroll-view scroll-y="true" >
			<view v-for="(d, i) in list" :key="i">{{d.name}}</view>
		</scroll-view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				list: [
					{name: '111'},
					{name: '111'},
					{name: '111'},
					{name: '111'},
					{name: '111'},
					{name: '111'},
					{name: '111'},
					{name: '111'},
					{name: '111'},
					{name: '111'},
					{name: '111'},
					{name: '111'}
				]
			}
		},
		methods: {
			
		}
	}
</script>

<style>

</style>
