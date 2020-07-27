<template>
	<div id="app">
		<Navbar/>
		<Welcome/>
		<AboutMe/>
		<Services/>
		<Presential/>
		<Policy/>
		<ContactMe/>
		<Credit/>
	</div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Welcome from './components/Welcome.vue';
import AboutMe from './components/AboutMe.vue';
import Services from './components/Services.vue';
import Presential from './components/Presential.vue';
import Policy from './components/Policy.vue';
import ContactMe from './components/ContactMe';
import Credit from './components/Credit.vue';

export default {
	name: 'App',
	components: {
		Navbar,
		Welcome,
		AboutMe,
		Services,
		Presential,
		Policy,
		ContactMe,
		Credit
	}
}
</script>

<style tyle lang="scss" scope>
	@import './styles/normalize.scss';
	@import './styles/global.scss';
</style>
