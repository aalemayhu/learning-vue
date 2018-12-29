<template>
	<div id="app">
		<img alt="Vue logo" src="./assets/logo.png">
		<HelloWorld msg="Welcome to Your Vue.js App"/>
	</div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import VueJsonPretty from "vue-json-pretty";

export default {
	name: "app",
	components: {
		HelloWorld,
		VueJsonPretty
	}
};
</script>

 <vue-json-pretty
      :path="'res'"
      :data="{ key: 'value' }">
    </vue-json-pretty>


<style>
#app {
	font-family: "Avenir", Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
	margin-top: 60px;
}
</style>
