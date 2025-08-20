<script>
    import { redirect } from '@sveltejs/kit';
	import '../app.css';
</script>

<style>
	html {
		scroll-behavior: smooth;
	}

	hr {
		border: 1.25px solid maroon;
		width: 100vw;
	}
</style>

<nav class="mx-auto flex max-w-screen-md py-6 uppercase">
	<a href="#home" class="flex-1 font-bold capitalize">Isabela Elena</a>
	<a href="#about" class="px-2">About</a>
	<a href="#works" class="px-2">Works</a>
	<a href="#contact" class="px-2">Contact</a>
</nav>

<div class="mx-auto max-w-screen-md text-base/7">
	<slot />

<div id="contact">
	<footer>
		<hr>
		<h3 id="contact">have coffee with me ☕️</h3>
	
		<ul>
			<li><a href="mailto:isabelaelenang@gmail.com">Email</a></li>
	
			<li><a href="https://www.linkedin.com/in/isabelaelena/">LinkedIn</a></li>
		</ul>
	</footer>
</div>




</div>