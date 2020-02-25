<template>
	<div id="app">
    <nav-bar />
		<main-tab-bar />
		<router-view />
	</div>
</template>
<script>
import MainTabBar from "components/content/mainTabBar/MainTabBar";
import NavBar from "components/common/navbar/NavBar";

export default {
	components: {
    MainTabBar,
    NavBar
	}
};
</script>
<style>
@import "assets/css/base.css";
</style>
