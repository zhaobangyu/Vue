<template>
	<div>
		<h1 v-on:click="tap1">{{title}}</h1>
		<div>{{content}}</div>
	</div>
</template>

<script>
	export default {
		name: 'test',
		props: {
			title: {
				type: String,
				default: ""
			},
			content: {
				type: String,
				default: ""
			}
		},
		data() {
			return {
			}
		},
		methods: {
			tap1:function(){
				console.log("test.vue methods tap1");
				this.$emit('tap1', this.title);
			}
		}
	}
</script>
<style>
</style>
