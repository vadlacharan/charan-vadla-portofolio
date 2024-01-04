<script>
	import charan from "../../src/assets/charan.png"
	import { fade  } from "svelte/transition";
	import resume from "../../src/assets/resume-charan-vadla.pdf"
	import instagram from "../../src/assets/instagram.png"
	import github from "../../src/assets/github-logo.png"
	import email from "../../src/assets/email.png"
	import linkedin from "../../src/assets/linkedin.png"
	
</script>

<div class="flex mt-28  sm:flex-row flex-col-reverse justify-center items-center" id="about">
	
		<div class="sm:ml-32 ml-0 sm:w-0.6 w-screen p-7 text-justify text-xl font-thin text-white variant-glass-primary rounded-xl"><span><h2 class="h2 variant-filled-secondary p-4 mt-3 mb-3 rounded-md flex justify-center">
			ABOUT ME
		</h2></span>I'm <b>Charan Vadla</b>, a Computer Science enthusiast with a passion for crafting innovative solutions through code. Proficient in <b>C, C++, Python, and Java,</b>  my journey spans from predictive modeling for financial institutions using <b>Machine Learning</b>  to designing intuitive bank system. With a strong foundation in web development encompassing <b> HTML, CSS, JavaScript</b>, and expertise in frameworks like <b>Svelte and Svelte-kit</b> , I've built secure and personalized applications, integrating robust database management using <b> PRISMA ORM </b> for <b>MySQL, PostgreSQL, Google Firestore, PocketBase DB</b> . My commitment to excellence extends to a C-based E-commerce application, where I employed advanced <b>Data Structures and Algorithms</b>  for efficient functionality. Certified in Supervised Machine Learning, Database Management, and skilled in various Python libraries, I thrive on merging technical acumen with creativity to drive impactful solutions.
				<br>
			<button class="btn font-medium variant-glass-tertiary mt-4 "><a href="{resume}" download="resume-charan">download Resume</a></button>
		</div>
		<div class="container m-10 pr-10 pl-10 pb-10 sm:ml-32 ">
			<img src="{charan}" alt="" class="rounded-full z-10" transition:fade>
		</div>
</div>




<!--PROJECTS-->

<div id="projects"></div>
<div class="sm:m-40  flex flex-col mt-36">
	<div>
		<h1 class="h1 flex justify-center  rounded-none h-20 items-center">PROJECTS</h1>
	</div>

	<div class="flex flex-col sm:flex-row   ">
		<div class="  rounded-3xl m-6 text-justify p-5 mb-6 sm:w-1/3 text-white transition variant-outline-secondary">
			<h3 class="h3 flex justify-center ">Bank Management System using Java</h3>
			<div class=" mt-3 text-xl font-thin">
				I crafted a robust <b> Java-based Bank Management System</b>, intricately connected to a  MySQL database via <b> JDBC</b> for seamless data management. The <b>Java Swing GUI</b> , built with an object-oriented approach, ensures an intuitive and efficient interface, enhancing user interaction and functionality. This project showcases my expertise in <b> object-oriented programming with Java</b>, adept database integration, and skillful GUI design, reflecting a commitment to delivering sophisticated and user-centric software solutions.
			</div>
		</div>
	
		<div class="  rounded-3xl m-6 text-justify p-5 mb-6 sm:w-1/3  text-white transition variant-outline-secondary">
			<h3 class="h3 flex justify-center">Personalized Todo Website</h3>
			<div class=" mt-3 text-xl font-thin">
				I developed a Personalized Todo Website featuring robust User Authentication. Utilizing <b>Svelte</b>  as the front-end framework alongside <b>HTML, CSS, JS, and Tailwind CSS</b> , I ensured a dynamic and personalized user interface. The back-end, powered by Vite-based <b>SvelteKit</b> , seamlessly integrates <b>Pocketbase</b>  as the database leveraging a secure back-end setup, resulting in an intuitive and secure platform for managing tailored task lists.
			</div>

			<div class="flex justify-start">
				<button class="btn variant-outline-primary mt-3 rounded-xl hover:variant-glass-primary"><a href="https://todos-app-vert.vercel.app/">View</a></button>
			</div>
			
		</div>
	
		<div class="  rounded-3xl m-6 text-justify p-5 mb-6 sm:w-1/3 text-white transition variant-outline-secondary">
			<h3 class="h3 flex justify-center">Bank Loan Approval Prediction</h3>
			<div class=" mt-3 text-xl font-thin">
				Developed a predictive model for Bank Loan Approval utilizing the <b>SVM</b> . Leveraging Python's libraries such as <b> Pandas and NumPy</b> for data manipulation and handling. Visual insights were brought to life using <b>Seaborn</b> . This project showcases <b> Python programming</b> , and data visualization techniques, aimed at delivering accurate and actionable predictions.
			</div>
		
		</div>
	</div>
	
</div>


<!--SKILLS-->
<div  class="flex mt-28   flex-col " id="skills">
		<h1 class="h1 flex justify-center mb-6">BADGES</h1>

		<div class="badge h-36 mb-8 variant-glass-primary rounded-none m-4 flex sm:mr-96 sm:ml-96 flex-col sm:flex-row">
			<div class="text-xl">Supervised Machine Learning</div>
			<div class=" font-thin m-2 text-xl "><i>- Coursera</i></div>
			<button class="btn variant-glass-secondary m-2"><a href="https://coursera.org/share/bc59f30733f2891286baf903303911f4">view certificate</a></button>
		</div>

		<div class="badge h-36 mb-8 variant-glass-primary rounded-none m-4 sm:mr-96	 sm:ml-96 flex flex-col sm:flex-row">
			<div class="text-xl">Database Management System</div>
			<div class=" font-thin m-2 text-xl "><i>- NPTEL</i></div>
		</div>

		<div class="badge h-36 mb-8 variant-glass-primary rounded-none m-4 sm:mr-96 sm:ml-96 flex flex-col sm:flex-row">
			<div class="text-xl">Data Structures and Algorithms</div>
			<div class=" font-thin m-2 text-xl "><i>- edX</i></div>
			<button class="btn variant-glass-secondary m-2"><a href="https://courses.edx.org/certificates/f3f41788a21c446fae84e2636ba4c433">view certificate</a></button>
		</div>

		<div class="badge h-36 mb-10 variant-glass-primary rounded-none m-4 sm:mr-96 sm:ml-96 flex flex-col sm:flex-row ">
			<div class="text-xl">Introduction to Java Programming</div>
			<div class=" font-thin m-2 text-xl "><i>- edX</i></div>
			<button class="btn variant-glass-secondary m-2"><a href="https://courses.edx.org/certificates/960e11f87f5c48dd8c08b9bafa313b14">view certificate</a></button>
		</div>
		
</div>




<!--CONTACTS-->
<h1 class="h1 flex justify-center mb-6 mt-28">CONTACT</h1>
<div class="flex justify-center ">
	<div id="contact" class=" h-0.7 w-screen mt-8 flex items-center bg-slate-900 sm:flex-row justify-around flex-col rounded-2xl">

		<div class=" pl-3 pr-3 text-md pt-2 pb-2 h-12 w-64 variant-glass-tertiary m-6 font-thin rounded-2xl flex items-center ">
			<img src="{linkedin}" class="h-8 w-8" alt="">
			<a href="https://www.linkedin.com/in/charan-vadla-14932524b" class="ml-8">Charan Vadla</a>
		</div>

		<div class=" pl-3 pr-3 text-md pt-2 pb-2 h-12 w-64 variant-glass-tertiary m-6 font-thin rounded-2xl flex items-center ">
			<img src="{github}" class="h-8 w-8" alt="">
			<a href="https://github.com/vadlacharan" class="ml-4">/vadlacharan</a>
		</div>

		<div class=" pl-3 pr-3 text-md pt-2 pb-2 h-12 w-64 variant-glass-tertiary m-6 font-thin rounded-2xl flex items-center ">
			<img src="{email}" class="h-8 w-8" alt="">
			<a href="/" class="ml-4 disabled ">charanvadla27@gmail.com</a>
		</div>

		<div class=" pl-3 pr-3 text-md pt-2 pb-2 h-12 w-64 variant-glass-tertiary m-6 font-thin rounded-2xl flex items-center ">
			<img src="{instagram}" class="h-8 w-8" alt="">
			<a href="https://www.instagram.com/charan_vishwakarma_" class="ml-4">charan_vishwakarma</a>
		</div>

		<div class="mb-28"></div>
	</div>
	
</div>

