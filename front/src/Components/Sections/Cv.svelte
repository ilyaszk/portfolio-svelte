<script>
import pp from '$lib/images/pp.png';
</script>

<section class="min-h-screen w-full mx-auto flex flex-col justify-around pt-12 pb-12" id="curriculum">
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
			<img src={pp} alt="Ilyas Zahaf Kradra" class="md:w-full pt-1 object-cover w-1/2">
			<p class="text-xl md:text-3xl font-titre text-left mb-0 pb-0 font-extrabold">
				Ilyas Zahaf Kradra
			</p>
			<p class="text-lg font-titre text-left text-blue-400 font-normal">LYON, FRANCE</p>
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
