<template>
	<view>
		<view class="uni-list-cell">
			<view class="uni-list-cell-let">
				<view class="uni-label-text">姓名</view>
			</view>
			<view class="uni-list-cell-db">
				<input class="uni-input" type="text" :disabled="true" :value="name" name="name"/>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				name:""
			}
		},
		onLoad:function(option){
			console.log(option.id);
			console.log(option.name);
			this.name=option.name;
			
		},
		methods: {
			
		}
	}
</script>

<style>

</style>
