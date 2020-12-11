<template>
	<div id="app">
		<img alt="Vue logo" src="./assets/logo.png">
		<test title="新闻标题" content="新闻内容" @tap1="tap1"> </test>
	</div>
</template>

<script>
	import test from './components/test.vue'

	export default {
		name: 'App',
		components: {
			test
		},
		methods: {
			tap1: function(e) {
				console.log("App.vue methods tap1 e=" + e);
			}
		}
	}
</script>

<style>
	#app {
		font-family: Avenir, Helvetica, Arial, sans-serif;
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
		text-align: center;
		color: #2c3e50;
		margin-top: 60px;
	}
</style>
