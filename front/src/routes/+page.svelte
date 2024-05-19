<script xmlns="http://www.w3.org/1999/html">
	import Home from '../Components/Sections/Home.svelte';
	import Presentation from '../Components/Sections/Presentation.svelte';
	import Cv from '../Components/Sections/Cv.svelte';
	import Project from '../Components/Sections/Project.svelte';
	import Footer from '../Components/Sections/Footer.svelte';
	import Slash from '../Components/Items/Slash.svelte';
</script>

<svelte:head>
	<title>Ilyas Zahaf Kradra - Fullstack Developer in Lyon, France</title>
	<meta name="description"
				content="My name is Ilyas Zahaf Kradra, and I am a Fullstack Developer based in Lyon, France. Welcome to my portfolio,
				where you can explore my presentation, curriculum vitae, projects, and contact information. Dive into my professional
				journey to discover my skills in front-end and back-end development, and see the innovative projects I've worked on.
				Contact me to discuss potential collaborations or opportunities.">
	<meta name="keywords"
				content="Ilyas Zahaf Kradra, Zahaf Kradra, Ilyas Zahaf, Portfolio, Fullstack Developer, Web Developer, Developer, VueJS, ReactJS, Lyon, France, Fullstack">
	<meta property="og:title" content="Ilyas Zahaf Kradra - Fullstack Developer in Lyon, France">
	<meta property="og:description"
				content="Explore my portfolio to discover my skills in front-end and back-end development, and see the innovative projects I've worked on.">
	<meta name="author" content="Ilyas Zahaf Kradra">
</svelte:head>

<!--section Accueil-->
	<Home />
	<Slash />
	<Presentation />
	<Slash />
	<Cv />
	<Slash />
	<Project />
	<Slash />
	<Footer />
