<template>
	<div>
		<h1>{{title}}</h1>
		<div>{{content}}</div>
		<button class="red" v-on:click="clicknow()"> 数值: {{counter}} </button>
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
				counter: 0
			}
		},
		methods: {
			clicknow() {
				this.counter += 1;
				console.log("counter=" + this.counter);
			}
		}
	}
</script>
<style>
	.red {
		color: red;
	}
</style>
