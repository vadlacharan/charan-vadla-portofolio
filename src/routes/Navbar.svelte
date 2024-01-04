<script>
    	function scrollIntoView({ target }) {
		const el = document.querySelector(target.getAttribute('href'));
		if (!el) return;
    el.scrollIntoView({
      behavior: 'smooth'
    });
  }
</script>

<div class="navbar flex w-screen items-center h-20 bg-surface-900 fixed top-0 z-20">
    <div>
        <h2 class="h2 sm:pl-2 flex justify-center items-center sm:w-80 ml-28 ">CHARAN VADLA</h2>
    </div>
    
    <div class="nav-group sm:flex hidden sm:last:ml-auto sm:mr-10">
        <a href="#about" on:click|preventDefault={scrollIntoView} class="a font-bold p-2 m-2 transition hover:variant-filled-primary ">ABOUT ME</a>
        <a href="#projects" on:click|preventDefault={scrollIntoView} class="a font-bold p-2 m-2  transition hover:variant-filled-primary ">PROJECTS</a>
        <a href="#skills" on:click|preventDefault={scrollIntoView} class="a font-bold p-2 m-2 transition hover:variant-filled-primary ">CERTIFICATIONS</a>
        <a href="#contact" on:click|preventDefault={scrollIntoView} class="a font-bold p-2 m-2 transition variant-filled-error hover:variant-filled-success ">CONTACTS</a>
    </div>
</div>


<div class=" fixed bottom-0 w-screen bg-surface-600 sm:hidden  h-14 z-10">
    <div class="flex">
        <a href="#about" on:click|preventDefault={scrollIntoView} class="a font-bold flex w-1/4 h-14 justify-center items-center transition activcentere:variant-filled-primary ">ABOUT</a>
        <a href="#projects" on:click|preventDefault={scrollIntoView} class="a font-bold flex w-1/4 h-14 justify-center items-center transition active:variant-filled-primary ">PROJECTS</a>
        <a href="#skills" on:click|preventDefault={scrollIntoView} class="a font-bold flex w-1/4 h-14 justify-center items-center transition active:variant-filled-primary ">BADGES</a>
        <a href="#contact" on:click|preventDefault={scrollIntoView} class="a font-bold flex w-1/4 h-14 justify-center items-center transition variant-filled-error">CONTACTS</a>
    </div>
</div>



<!--SKILLS-->


