<template>
	<div id="app">

		<NavBar/>
		<router-view />
		<footer-components />
	</div>
</template>

<script>
import FooterComponents from './components/FooterComponents.vue'
import NavBar from './components/NavBar.vue'

export default {
	name: 'App',

	mounted() {
		// Agregar el listener al evento resize cuando el componente se monta
		window.addEventListener('resize', this.handleResize)
	},

	methods: {
		handleResize() {
			// Esta función se ejecutará cada vez que la ventana se redimensione
			this.mobileView = window.innerWidth <= 768
		},
	},
	components: {
		NavBar,
		FooterComponents,
	},
	data() {
		return {
			nav: true,
			mobileView: false,
		}
	},
}
</script>

<style>
* {
	margin: 0;
	padding: 0;
	box-sizing: border-box;
	font-family: 'Helvetica', sans-serif;
}

.main-container {
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	height: 100vh;
	background-image: url(../public/img/rezised/Backgroundmin_Hero.png);
	background-size: cover;
	min-width: 550px;
}

h1 {
	color: white;
	font-size: 30px;
	text-align: center;
	margin-top: 100px;
}

#nav-icon {
	padding: 10px 10px 20px;
	margin-right: 10px;
	cursor: pointer;
}
i {
	font-size: 2rem;
	color: var(--clr-Beige-Light, #f0c986);
}
</style>
