<script lang="ts">
	import Banner from '$lib/elena.svelte';
</script>

<nav class="mx-auto flex max-w-screen-md py-4 uppercase">
	<a href="#" class="flex-1 font-bold capitalize">Isabela Elena</a>
	<a href="#" class="px-2">About</a>
	<a href="#" class="px-2">Works</a>
	<a href="#" class="px-2">Contact</a>
</nav>

<div class="mx-auto max-w-screen-md pb-72">
	<div class="flex space-x-4">
		<div class="flex flex-col place-content-center">
			<h1 class="font-serif text-3xl">Advocating progress through technology and innovation</h1>
			<p class="mt-8 font-serif">
				Currently working as a Product Manager in the public sector across North America
			</p>
			<a class="mt-8 text-sm italic" href="/resume.pdf">Download my resume 〉</a>
		</div>
		<!-- <div class="min-h-96 min-w-80 bg-gray-200 inline-block"></div> -->
		<Banner />
	</div>

	<h2 class="font-bold">get to know me</h2>

	<p class="pt-4">
		Hi, I'm Elena. I like to think, research (surfing the web included), design, build, annnddd
		repeat.
	</p>

	<p class="pt-4">
		I want my work to matter and will go the extra mile to create positive impact in my community
		around me through whatever I do. Also currently trying to put more of my thinking into words.
	</p>

	<p class="pt-4">Love learning about new stuff. Connect with me :)</p>

	<h2 class="font-bold">works & projects</h2>

	<div class="relative max-w-full pt-4">
		<div class="flex space-x-2 overflow-x-auto">
			<div class="inline-block min-h-40 min-w-40 bg-gray-200"></div>
			<div class="inline-block min-h-40 min-w-40 bg-gray-200"></div>
			<div class="inline-block min-h-40 min-w-40 bg-gray-200"></div>
			<div class="inline-block min-h-40 min-w-40 bg-gray-200"></div>
			<div class="inline-block min-h-40 min-w-40 bg-gray-200"></div>
			<div class="inline-block min-h-40 min-w-40 bg-gray-200"></div>
			<div class="inline-block min-h-40 min-w-40 bg-gray-200"></div>
			<div class="inline-block min-h-40 min-w-40 bg-gray-200"></div>
			<div class="inline-block min-h-40 min-w-40 bg-gray-200"></div>

			<!-- Padding so that the gradient effect does not overlap with the last element -->
			<div class="inline-block min-h-40 min-w-20"></div>
		</div>

		<!-- Fading gradient -->
		<div
			class="pointer-events-none absolute right-0 top-0 h-full w-16 bg-gradient-to-l from-gray-100 to-transparent"
		></div>
	</div>

	<!-- TODO -->

	<h2 class="font-bold">have coffee with me ☕️</h2>

	<ul>
		<li><a href="mailto:isabelaelenang@gmail.com">Email</a></li>
		<!-- TODO -->
		<li><a href="#">LinkedIn</a></li>
	</ul>
</div>

<style lang="postcss">
	:global(html) {
		background-color: theme(colors.gray.100);
	}

	h2 {
		@apply pt-4;
	}
</style>
