<script>
import wine from '$lib/images/Wine.png';
import portFolio from '$lib/images/firstPortfolio.png';
import newPortFolio from '$lib/images/portFolio.png';
</script>

<section class="min-h-screen w-full mx-auto py-12 " id="projects">
	<div class="flex">
		<p class="text-5xl md:text-8xl font-titre text-center text-blue-400 font-extrabold">
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
