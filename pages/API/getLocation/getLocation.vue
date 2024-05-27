<template>
	<view>
		<view class="uni-page-head">
			<view class="uniui-page-head-title">getLocation</view>
		</view>
		<view>
			<map :latitude="latitude" :longitude="longitude" :markers="covers"></map>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				latitude:"",
				longitude:"",
				covers:[
					{
						latitude:"",
						longitude:"",
					}
				]
				
			}
		},
		methods: {
			
		}
	}
</script>

<style>

</style>
