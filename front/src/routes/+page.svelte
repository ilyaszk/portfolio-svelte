<script xmlns="http://www.w3.org/1999/html">
	import pp from '$lib/images/pp.jpg';
	import wine from '$lib/images/Wine.png';
	import portFolio from '$lib/images/firstPortfolio.png';
	import newPortFolio from '$lib/images/portFolio.png';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="Me" content="presentation of my person" />
</svelte:head>

<!--section Accueil-->
<section class="flex flex-col justify-center items-center min-h-screen w-full md:pb-8">
	<!-- Modifier la taille du titre en fonction de la taille de l'écran -->
	<p
		class="font-titre text-[6rem] md:text-[18rem] lg:text-[25rem] w-full text-center  text-blue-400 font-extrabold">
		PORTFOLIO</p>
	<div class="flex flex-col md:flex-row justify-center items-center w-full  gap-x-12">
		<!-- Modifier la taille du titre en fonction de la taille de l'écran -->
		<p class="md:text-5xl  lg:text-6xl text-2xl
			w-fit text-nowrap font-titre text-center text-blue-400 font-extrabold">Ilyas Zahaf Kradra

		</p>
		<div class="flex flex-col-reverse md:flex-row justify-center items-center w-fit  gap-x-12">
				<span class="animate-pulse text-blue-400">
                    <svg class="w-16 md:w-20 h-16 md:h-20 inline-block" fill="none" stroke="currentColor"
												 viewBox="0 0 24 24"
												 xmlns="http://www.w3.org/2000/svg">
                        <path stroke-linecap="square" stroke-linejoin="round" stroke-width="2"
															d="M19 9l-7 7-7-7"></path>
                    </svg>
                </span>
			<p class="md:text-5xl  lg:text-6xl text-2xl
			w-fit text-nowrap font-titre text-center text-blue-400 font-extrabold"> Fullstack Developer
			</p>
		</div>

	</div>
</section>

<hr class="slash ">
<!--section Presentation-->
<section class="min-h-screen w-full mx-auto pt-12" id="presentation">
	<!--	<div class="flex flex-col justify-center items-center mb-12">-->
	<!--		&lt;!&ndash; Modifier la taille du titre en fonction de la taille de l'écran &ndash;&gt;-->
	<!--		<p class="text-5xl md:text-8xl font-titre text-center text-blue-400 font-extrabold">-->
	<!--			Presentation-->
	<!--		</p>-->
	<!--		<span class="mt-2">-->
	<!--            <svg class="w-20 h-20 text-blue-400" xmlns="http://www.w3.org/2000/svg" viewBox="0 4 20 24" fill="currentColor">-->
	<!--                <path d="M7 7h8.586L5.293 17.293l1.414 1.414L17 8.414V17h2V5H7v2z" />-->
	<!--            </svg>-->
	<!--        </span>-->
	<!--	</div>-->
	<div class="flex">
		<p class="text-5xl md:text-8xl font-titre text-center text-blue-400 font-extrabold">
			Presentation
		</p>
		<span>
		<svg class="md:w-32 md:h-32	 w-14 h-16 text-blue-400" xmlns="http://www.w3.org/2000/svg" viewBox="0 4 20 24"
				 fill="currentColor"
		>
			<path
				d="M7 7h8.586L5.293 17.293l1.414 1.414L17 8.414V17h2V5H7v2z" />
		</svg>
		</span>
	</div>
	<article class="grid gap-12 md:grid-cols-2">
		<!-- Les classes de taille de police sont ajustées pour les écrans de différentes tailles -->
		<p class="text-lg md:text-xl lg:text-2xl xl:text-2xl text-left font-sans font-normal tracking-tighter">
			I'm Ilyas a
			<span class="text-blue-400 font-bold">Master's</span> student, I am currently pursuing a degree in
			<span class="text-blue-400 font-bold">Web Engineering</span> while simultaneously gaining practical experience
			through an apprenticeship as a
			<span class="text-blue-400 font-bold">Full Stack Developer</span>. With just a year left to complete my studies,
			I
			find myself deeply immersed in the world of technology and development.
		</p>
		<!-- Les classes de taille de police sont ajustées pour les écrans de différentes tailles -->
		<p class="text-lg md:text-xl lg:text-2xl xl:text-2xl text-left font-sans font-normal tracking-tighter">
			My passion for technology and coding has been a driving force throughout my academic and professional journey. I
			am constantly exploring new frameworks and languages to broaden my skill set and stay abreast of industry
			trends.
			At present, my proficiency lies in
			<span class="text-blue-400 font-bold">Vue.js</span> and
			<span class="text-blue-400 font-bold">Tailwind CSS</span>, which I employ extensively in my projects.
			Additionally, I have a strong command of
			<span class="text-blue-400 font-bold">Java</span>, honed through both coursework and practical applications.
		</p>
		<!-- Les classes de taille de police sont ajustées pour les écrans de différentes tailles -->
		<p class="text-lg md:text-xl lg:text-2xl xl:text-2xl text-left font-sans font-normal tracking-tighter">
			My current focus is on enhancing my development skills, particularly in
			<span class="text-blue-400 font-bold">Node.js with Express</span> and in
			<span class="text-blue-400 font-bold">Vue.js</span> /
			<span class="text-blue-400 font-bold">Tailwind CSS</span> to be able to deliver robust web solutions. Above all,
			I
			want to become versatile and able to adapt to any situation that may arise.
		</p>
		<!-- Les classes de taille de police sont ajustées pour les écrans de différentes tailles -->
		<p class="text-lg md:text-xl lg:text-2xl xl:text-2xl text-left font-sans font-normal tracking-tighter">
			In essence, I thrive on the challenge of learning and adapting to
			<span class="text-blue-400 font-bold">new technologies</span>. Whether it's mastering a new framework or diving
			into the intricacies of backend development, I approach each opportunity with enthusiasm and dedication. My
			journey
			as a developer is not just about acquiring technical skills but also about embracing the continuous
			<span class="text-blue-400 font-bold">evolution of technology</span> and its endless possibilities.
		</p>
	</article>
</section>

<hr class="slash ">

<!--secttion Curiculum-->

<section class="min-h-screen w-full mx-auto flex flex-col justify-around pt-12 pb-12" id="curriculum">
	<!--	<div class="flex flex-row justify-center items-center mb-12">-->
	<!--		&lt;!&ndash; Modifier la taille du titre en fonction de la taille de l'écran &ndash;&gt;-->
	<!--		<p class="text-5xl md:text-8xl font-titre text-center text-blue-400 font-extrabold">-->
	<!--			Curriculum Vitae-->
	<!--		</p>-->
	<!--		<span class="mt-2">-->
	<!--            <svg class="w-20 h-20 text-blue-400" xmlns="http://www.w3.org/2000/svg" viewBox="0 4 20 24" fill="currentColor">-->
	<!--                <path d="M7 7h8.586L5.293 17.293l1.414 1.414L17 8.414V17h2V5H7v2z" />-->
	<!--            </svg>-->
	<!--        </span>-->
	<!--	</div>-->
	<div class="flex">
		<p class="text-5xl md:text-8xl font-titre text-center text-blue-400 font-extrabold">
			Curriculum Vitae
		</p>
		<span>
		<svg class="md:w-32 md:h-32	 w-14 h-16 text-blue-400" xmlns="http://www.w3.org/2000/svg" viewBox="0 4 20 24"
				 fill="currentColor"
		>
			<path
				d="M7 7h8.586L5.293 17.293l1.414 1.414L17 8.414V17h2V5H7v2z" />
		</svg>
		</span>
	</div>
	<article class="grid gap-12 md:grid-cols-4 ">
		<!-- Les classes de taille de police sont ajustées pour les écrans de différentes tailles -->
		<div class="flex flex-col items-start">
			<img src={pp} alt="Ilyas Zahaf Kradra" class="w-full pt-1 object-cover">
			<p class="text-xl md:text-3xl font-titre text-left mb-0 pb-0 font-extrabold">
				Ilyas Zahaf Kradra
			</p>
			<p class="text-lg font-titre text-left text-blue-400 font-normal">LYON, FRANCE</p>
			<a class="text-lg font-titre text-left font-normal" href="tel:+33652525252">+33 6 52 52 52 52</a>
			<a class="text-lg font-titre text-left font-normal" href="mailto:Ilyas.zahafkradra.pro@gmail.com">Ilyas.zahafkradra.pro@gmail.com</a>
			<a class="text-lg font-titre text-left font-normal" href="https://github.com/ilyaszk" target="_blank">GitHub</a>
			<a class="text-lg font-titre text-left font-normal" href="https://www.linkedin.com/in/ilyas-zahaf-kradra/"
				 target="_blank">LinkedIn</a>
		</div>
		<!-- Les classes de taille de police sont ajustées pour les écrans de différentes tailles -->
		<div class="flex flex-col justify-start">
			<p class="text-xl md:text-3xl font-titre text-left font-extrabold text-blue-400">
				Skills
			</p>
			<p class="text-[1.8rem] font-titre text-left underline font-medium">
				FRONT
			</p>
			<p class=" text-xl text-left font-sans font-medium tracking-tighter">
				Vue.js
			</p>
			<p class=" text-xl text-left font-sans font-medium tracking-tighter">
				Angular 2+ / AngularJS
			</p>
			<p class=" text-xl text-left font-sans font-medium tracking-tighter">
				Lit.js
			</p>
			<p class=" text-xl text-left font-sans font-medium tracking-tighter">
				Svelte
			</p>
			<p class=" text-xl text-left font-sans font-medium tracking-tighter">
				Tailwind CSS / Bootstrap
			</p>
			<p class=" text-xl text-left font-sans font-medium tracking-tighter">
				CSS3 / SASS
			</p>
			<p class=" text-xl text-left font-sans font-medium tracking-tighter">
				JavaScript / TypeScript
			</p>

			<p class="text-[1.8rem] font-titre text-left underline font-medium pt-4">
				BACK
			</p>
			<p class=" text-xl text-left font-sans font-medium tracking-tighter">
				Java / Hibernate
			</p>
			<p class=" text-xl text-left font-sans font-medium tracking-tighter">
				Symfony
			</p>
			<p class=" text-xl text-left font-sans font-medium tracking-tighter">
				Node.js / Express
			</p>
			<p class=" text-xl text-left font-sans font-medium tracking-tighter">
				PostgreSQL / MySQL / MongoDB
			</p>

			<p class="text-[1.8rem] font-titre text-left underline font-medium pt-4">
				OTHERS
			</p>
			<p class=" text-xl text-left font-sans font-medium tracking-tighter">
				Git / Docker
			</p>
			<p class=" text-xl text-left font-sans font-medium tracking-tighter">
				Agile / Scrum
			</p>
			<p class=" text-xl text-left font-sans font-medium tracking-tighter">
				Figma
			</p>

		</div>
		<div class="flex flex-col justify-start">
			<p class="text-xl md:text-3xl font-titre text-left font-extrabold text-blue-400">
				Experiences
			</p>
			<p class="text-[1.8rem] font-titre text-left underline font-medium">
				Full Stack Developer
			</p>
			<p class=" text-md text-left font-sans font-medium tracking-tighter">
				Apprenticeship, PWA Assurance, Lyon(69)
			</p>
			<p class=" text-sm text-left font-sans font-medium tracking-tighter">
				( 2022 - Today )
			</p>
			<p class=" text-xl text-left font-sans font-bold text-blue-400 tracking-tighter">
				Software Migration:
			</p>
			<ul class="list-disc pl-5">
				<li class=" text-md text-left font-sans font-medium tracking-tighter">
					Updated old Java 8 and Swing client-server software to a modern web app using Java 17/21 and AngularJS.
				</li>
				<li class=" text-md text-left font-sans font-medium tracking-tighter">
					Developed new features and improved existing ones.
				</li>
				<li class=" text-md text-left font-sans font-medium tracking-tighter">
					Fixed bugs and optimized performance.
				</li>
			</ul>
			<p class=" text-xl text-left font-sans font-bold text-blue-400 tracking-tighter">
				Website Overhaul:
			</p>
			<ul class="list-disc pl-5">
				<li class=" text-md text-left font-sans font-medium tracking-tighter">
					Revamped company website with LitJS.
				</li>
				<li class=" text-md text-left font-sans font-medium tracking-tighter">
					Designed mockups and prototypes using Figma for a better user experience.
				</li>
				<li class=" text-md text-left font-sans font-medium tracking-tighter">
					Ensured website responsiveness across different devices.
				</li>
			</ul>
			<p class="text-[1.8rem] font-titre text-left underline font-medium pt-4">
				Web Developer
			</p>
			<p class=" text-md text-left font-sans font-medium tracking-tighter">
				Internship, PWA Assurance, Lyon(69)
			</p>
			<p class=" text-sm text-left font-sans font-medium tracking-tighter">
				( 2022 for 3 months )
			</p>
			<p class=" text-xl text-left font-sans font-bold text-blue-400 tracking-tighter">
				Migration of a web application:
			</p>
			<ul class="list-disc pl-5">
				<li class=" text-md text-left font-sans font-medium tracking-tighter">
					PoC of a migration from an AngularJS web app to a VueJS web app.
				</li>
				<li class=" text-md text-left font-sans font-medium tracking-tighter">
					Documentation of the migration process.
				</li>
			</ul>
		</div>
		<div class="flex flex-col justify-start">
			<p class="text-xl md:text-3xl font-titre text-left font-extrabold text-blue-400">
				Degrees
			<p class="text-[1.8rem] font-titre text-left underline font-medium">
				Master's Degree in Web Engineering
			</p>
			<p class=" text-md text-left font-sans font-medium tracking-tighter">
				ESGI, Lyon(69)
			</p>
			<p class=" text-sm text-left font-sans font-medium tracking-tighter">
				( 2023 - 2025 )
			</p>
			<p class=" text-lg text-left font-sans font-medium tracking-tighter">
				Work-Study Program
			</p>
			<p class="text-[1.8rem] font-titre text-left underline font-medium pt-4">
				Bachelor's Degree in Web Development
			</p>
			<p class=" text-md text-left font-sans font-medium tracking-tighter">
				IUT2, Grenoble(38)
			</p>
			<p class=" text-sm text-left font-sans font-medium tracking-tighter">
				( 2022 - 2023 )
			</p>
			<p class=" text-lg text-left font-sans font-medium tracking-tighter">
				Work-Study Program
			</p>
			<p class="text-[1.8rem] font-titre text-left underline font-medium pt-4">
				DUT in Computer Science
			</p>
			<p class=" text-md text-left font-sans font-medium tracking-tighter">
				IUT2, Grenoble(38)
			</p>
			<p class=" text-sm text-left font-sans font-medium tracking-tighter">
				( 2020 - 2022 )
			</p>
			<p class=" text-lg text-left font-sans font-medium tracking-tighter">
				Exploration of Computer Science and Web Development
			</p>
			<p class="text-[1.8rem] font-titre text-left underline font-medium pt-4">
				Baccalaureate in Science
			</p>
			<p class=" text-md text-left font-sans font-medium tracking-tighter">
				Lycée La Saulaie, Saint-Marcellin(38)
			</p>
			<p class=" text-sm text-left font-sans font-medium tracking-tighter">
				( 2019 )
			</p>
			<p class=" text-lg text-left font-sans font-medium tracking-tighter">
				Specialization in Physics and Chemistry
			</p>
		</div>
	</article>
</section>

<hr class="slash ">
<!--section Projects-->

<section class="min-h-screen w-full mx-auto py-12 " id="projects">
	<div class="flex">
		<p class="text-8xl font-titre text-center text-blue-400 font-extrabold">
			Projects</p>
		<span>
		<svg class="md:w-32 md:h-32	 w-14 h-16 text-blue-400" xmlns="http://www.w3.org/2000/svg" viewBox="0 4 20 24"
				 fill="currentColor"
		>
			<path
				d="M7 7h8.586L5.293 17.293l1.414 1.414L17 8.414V17h2V5H7v2z" />
		</svg>
		</span>
	</div>
	<div class="flex flex-col gap-24">

		<article class="h-fit grid grid-cols-1 md:grid-cols-2 gap-12">
			<div class="flex flex-col justify-start ">

				<p class=" text-4xl font-titre text-left underline font-medium">
					Wine Degustation Workshop Management
				</p>
				<p class=" text-md text-left font-sans font-medium tracking-tighter">
					( 2024 ) School Project
				</p>
				<!--			techno-->
				<p class=" text-lg text-left font-sans font-medium tracking-tighter">
					Technologies:
				</p>
				<p class=" text-lg text-left font-sans font-bold tracking-tighter text-blue-400">
					Vue.js, Nuxt.js, Symfony, MySQL, Tailwind CSS
				</p>
				<!--			description-->
				<p class=" text-lg text-left font-sans font-medium tracking-tighter">
					Description:
				</p>
				<p class=" text-lg text-left font-sans font-medium tracking-tighter">
					The project aims to develop a web platform facilitating wine tasting workshop management, encompassing
					online
					registration, workshop scheduling, and wine inventory control. Users can register for workshops via online
					forms, receiving automatic email confirmations. An interactive calendar displays available workshop dates,
					with
					administrators empowered to create, modify, and cancel workshops, including setting parameters like
					participant
					limits and associated wines. The platform facilitates wine inventory management, allowing addition,
					modification, and deletion of wines, along with basic information entry and stock tracking. Participants can
					make reservations, with automatic reminders and administrative oversight. Payment options include PayPal,
					Lydia,
					or Paylib, ensuring registration validation upon payment.
				</p>
			</div>
			<img src={wine} alt="Wine Degustation Workshop Management" class="w-full object-cover drop-shadow-2xl ">
		</article>
		<article class="h-fit md:grid md:grid-cols-2 gap-12 flex flex-col-reverse  ">
			<img src={portFolio} alt="First Portfolio" class="w-full object-cover drop-shadow-2xl ">
			<div class="flex flex-col justify-start ">

				<p class=" text-4xl font-titre text-left underline font-medium">
					First Portfolio
				</p>
				<p class=" text-md text-left font-sans font-medium tracking-tighter">
					( 2023 ) Personal Project
				</p>
				<!--			techno-->
				<p class=" text-lg text-left font-sans font-medium tracking-tighter">
					Technologies:
				</p>
				<p class=" text-lg text-left font-sans font-bold tracking-tighter text-blue-400">
					Vue.js, Tailwind CSS
				</p>
				<!--			description-->
				<p class=" text-lg text-left font-sans font-medium tracking-tighter">
					Description:
				</p>
				<p class=" text-lg text-left font-sans font-medium tracking-tighter">
					My first portfolio was a personal project aimed at showcasing my skills and projects. The website was
					developed
					using Vue.js and Tailwind CSS, with a focus on responsive design and user experience. The portfolio features
					a
					home page introducing myself and my skills, a projects page detailing my work, and a contact page for
					reaching
					out. The site is designed to be visually appealing and easy to navigate, with a clean layout and intuitive
					interface. The project was an opportunity to apply my knowledge of front-end development and design
					principles,
					creating a professional and engaging online presence.
				</p>
			</div>
		</article>
		<!--		the last this portfolio to try a new framework Svelte-->
		<article class="h-fit grid grid-cols-1 md:grid-cols-2 gap-12">
			<div class="flex flex-col justify-start ">

				<p class=" text-4xl font-titre text-left underline font-medium">
					Portfolio
				</p>
				<p class=" text-md text-left font-sans font-medium tracking-tighter">
					( 2024 ) Personal Project
				</p>
				<!--			techno-->
				<p class=" text-lg text-left font-sans font-medium tracking-tighter">
					Technologies:
				</p>
				<p class=" text-lg text-left font-sans font-bold tracking-tighter text-blue-400">
					Svelte, Tailwind CSS
				</p>
				<!--			description-->
				<p class=" text-lg text-left font-sans font-medium tracking-tighter">
					Description:
				</p>
				<p class=" text-lg text-left font-sans font-medium tracking-tighter">
					My current portfolio is a personal project aimed at showcasing my skills and projects. The website was
					developed
					using Svelte and Tailwind CSS, with a focus on responsive design and user experience. The portfolio features
					a
					home page introducing myself and my skills, a projects page detailing my work, and a contact page for
					reaching
					out. The site is designed to be visually appealing and easy to navigate, with a clean layout and intuitive
					interface. The project was an opportunity to apply my knowledge of front-end development and design
					principles,
					creating a professional and engaging online presence.
				</p>
			</div>
			<img src={newPortFolio} alt="Portfolio" class="w-full object-cover drop-shadow-2xl ">
		</article>
	</div>
</section>
<hr class="slash">
<!--last section  Contact-->

<section class="h-fit w-full flex flex-col md:flex-row justify-between mx-auto py-12">
	<!--	<div class="flex flex-col justify-center items-center mb-8 md:mb-0">-->
	<!--		&lt;!&ndash; Modifier la taille du titre en fonction de la taille de l'écran &ndash;&gt;-->
	<!--		<p class="text-5xl md:text-8xl font-titre text-center text-blue-400 font-extrabold">-->
	<!--			Contact-->
	<!--		</p>-->
	<!--		<span class="mt-2">-->
	<!--            <svg class="w-20 h-20 md:w-32 md:h-32 text-blue-400" xmlns="http://www.w3.org/2000/svg" viewBox="0 4 20 24" fill="currentColor">-->
	<!--                <path d="M7 7h8.586L5.293 17.293l1.414 1.414L17 8.414V17h2V5H7v2z" />-->
	<!--            </svg>-->
	<!--        </span>-->
	<!--	</div>-->
	<div class="flex">
		<p class="text-8xl font-titre text-center text-blue-400 font-extrabold">
			Contact
		</p>
		<span>
		<svg class="md:w-32 md:h-32	 w-14 h-16 text-blue-400" xmlns="http://www.w3.org/2000/svg" viewBox="0 4 20 24"
				 fill="currentColor"
		>
			<path
				d="M7 7h8.586L5.293 17.293l1.414 1.414L17 8.414V17h2V5H7v2z" />
		</svg>
		</span>
	</div>
	<article class="grid grid-cols-1 md:grid-cols-2 gap-12">
		<div class="flex flex-col justify-start">
			<!-- Ajouter des classes pour ajuster la taille du texte en fonction de la taille de l'écran -->
			<p class="text-2xl md:text-4xl font-titre text-left underline font-medium">
				Links Parts
			</p>
			<!-- Les liens sont maintenant affichés en colonne sur les petits écrans -->
			<a class="text-lg md:text-xl text-left font-sans font-bold tracking-tighter" href="#presentation">
				Presentation
			</a>
			<a class="text-lg md:text-xl text-left font-sans font-bold tracking-tighter" href="#curriculum">
				Curriculum Vitae
			</a>
			<a class="text-lg md:text-xl text-left font-sans font-bold tracking-tighter" href="#projects">
				Projects
			</a>
		</div>
		<div class="flex flex-col justify-start">
			<!-- Ajouter des classes pour ajuster la taille du texte en fonction de la taille de l'écran -->
			<p class="text-2xl md:text-4xl font-titre text-left underline font-medium">
				Contact Information
			</p>
			<!-- Les informations de contact sont maintenant affichées en colonne sur les petits écrans -->
			<p class="text-lg md:text-xl text-left font-sans font-medium tracking-tighter">
				Location:
			</p>
			<p class="text-lg md:text-xl text-left font-sans font-bold tracking-tighter text-blue-400">
				Lyon, France
			</p>
			<p class="text-lg md:text-xl text-left font-sans font-medium tracking-tighter">
				Phone:
			</p>
			<a class="text-lg md:text-xl text-left font-sans font-bold tracking-tighter text-blue-400"
				 href="tel:+33652525252">
				+33 6 52 52 52 52
			</a>
			<p class="text-lg md:text-xl text-left font-sans font-medium tracking-tighter">
				Email:
			</p>
			<a class="text-lg md:text-xl text-wrap text-left font-sans font-bold tracking-tighter text-blue-400"
				 href="mailto:ilyas.zahafKradra.pro@gmail.com" target="_blank">
				ilyas.zahafKradra.pro@gmail.com
			</a>
		</div>
	</article>
</section>

<style>
    .slash {
        height: 10px;
        background-image: linear-gradient(45deg,
        hsla(0, 0%, 5%, 0),
        hsla(0, 0%, 5%, 0) 33.33%,
        rgb(96 165 250) 33.33%,
        rgb(96 165 250) 66.67%,
        hsla(0, 0%, 5%, 0) 66.67%,
        hsla(0, 0%, 5%, 0) 100%);
        background-size: 10px 100%;
        width: 100%;
    }
</style>
