<script>
	import { Icon, ArrowDown } from 'svelte-hero-icons';
</script>

<div
	class="min-h-screen flex flex-col items-center justify-center bg-gradient-to-br from-gray-800 to-gray-900 text-white"
>
	<header class="w-full py-6 text-center border-b border-gray-700">
		<h1 class="text-7xl font-extrabold mb-4 text-red-500 tracking-wide">Vocabulizer</h1>
		<p class="text-xl font-light tracking-wider">Your smart tool for unlocking language mastery</p>
	</header>

	<main class="flex flex-col items-center px-6 py-12 max-w-4xl text-center space-y-12">
		<h2 class="text-4xl font-bold mb-6">Download Your Copy</h2>
		<p class="text-lg mb-12 leading-relaxed">
			Download the latest version of Vocabulizer to start enhancing your language learning journey.
			Simply click the button below to get started.
		</p>

		<a
			href="/download"
			class="bg-red-500 text-white py-3 px-8 rounded-full text-lg font-semibold inline-flex items-center space-x-3 hover:bg-red-600 transition-all duration-300 shadow-lg transform hover:scale-105 active:scale-95"
		>
			<Icon src={ArrowDown} class="w-6 h-6" />
			<span class="ml-2">Download Now</span>
		</a>
	</main>

	<footer class="w-full py-8 mt-auto bg-gray-900 text-center">
		<p class="text-sm">© 2024 Vocabulizer. All Rights Reserved.</p>
		<nav class="flex justify-center space-x-4 text-sm mt-4">
			<a href="/terms" class="hover:underline">Terms</a>
			<a href="/privacy" class="hover:underline">Privacy</a>
			<a href="/contact" class="hover:underline">Contact</a>
		</nav>
	</footer>
</div>
