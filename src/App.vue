<template>
	<link rel="stylesheet" href="./src/assets/css/style.css">
	
	<div class="app">
		

		<!-- Sidebar -->
		<Sidebar />


		<!-- Content -->
		<router-view />
	</div>
</template>

<script setup>
import Sidebar from './components/Sidebar.vue'
</script>

<style lang="scss">

</style>