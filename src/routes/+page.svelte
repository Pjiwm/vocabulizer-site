<script>
	import '../app.css'; // Adjust path as necessary
	import { Icon, ArrowDown, ShoppingCart } from 'svelte-hero-icons';
</script>

<div
	class="min-h-screen flex flex-col items-center justify-center bg-gradient-to-br from-gray-800 to-gray-900 text-white"
>
	<!-- Header -->
	<header class="w-full py-6 text-center border-b border-gray-700">
		<h1 class="text-7xl font-extrabold mb-4 text-red-500 tracking-wide">Vocabulizer</h1>
		<p class="text-xl font-light tracking-wider">Smart tool for unlocking language mastery</p>
	</header>

	<!-- Supported Languages Section -->
	<section class="w-full px-6 py-12 max-w-4xl text-center">
		<h2 class="text-3xl font-semibold mb-6">Supported Languages</h2>
		<div class="flex flex-wrap justify-center gap-2">
			<!-- Language Bubbles -->
			<div
				class="bg-gray-600 text-white rounded-full py-2 px-4 flex items-center space-x-3 opacity-70 hover:opacity-100 transition-opacity"
			>
				<span>Japanese</span>
			</div>
			<div
				class="bg-gray-600 text-white rounded-full py-2 px-4 flex items-center space-x-3 opacity-70 hover:opacity-100 transition-opacity"
			>
				<span>German (WIP)</span>
			</div>
			<div
				class="bg-gray-600 text-white rounded-full py-2 px-4 flex items-center space-x-3 opacity-70 hover:opacity-100 transition-opacity"
			>
				<span>French (WIP)</span>
			</div>
			<div
				class="bg-gray-600 text-white rounded-full py-2 px-4 flex items-center space-x-3 opacity-70 hover:opacity-100 transition-opacity"
			>
				<span>Spanish (WIP)</span>
			</div>
		</div>
	</section>

	<!-- Main Section -->
	<main class="flex flex-col items-center px-6 py-12 max-w-4xl text-center space-y-12">
		<h2 class="text-4xl font-bold mb-6">Master Vocabulary Efficiently</h2>
		<p class="text-lg mb-12 leading-relaxed">
			Vocabulizer transforms complex texts into valuable learning resources. Advanced text analysis
			tools break down content and provide detailed word definitions, making language learning
			engaging and effective.
		</p>

		<!-- Download and Buy Containers -->
		<div class="flex flex-col md:flex-row gap-8 max-w-3xl mx-4">
			<!-- Download Container -->
			<div
				class="flex-1 bg-gray-700 rounded-lg p-8 shadow-lg transition-transform transform
				hover:scale-105 relative overflow-hidden border-4 border-transparent hover:border-red-500"
			>
				<div
					class="absolute inset-0 bg-gray-500 opacity-20 transition-opacity duration-300 group-hover:opacity-0"
				></div>
				<div class="relative z-10">
					<h3 class="text-2xl font-semibold mb-4">Download Now</h3>
					<p class="text-lg mb-6">
						Download the program and get the lite version for free. Experience how Vocabulizer can
						revolutionize language learning.
					</p>
					<a
						href="/download"
						class="bg-red-500 text-white py-3 px-8 rounded-full text-lg font-semibold inline-flex items-center space-x-3 hover:bg-red-600 transition-all duration-300 shadow-lg transform hover:scale-105 active:scale-95"
					>
						<Icon src={ArrowDown} class="w-6 h-6" />
						<span class="ml-2">Download Now</span>
					</a>
				</div>
			</div>

			<!-- Buy Container -->
			<div
				class="flex-1 bg-gray-700 rounded-lg p-8 shadow-lg transition-transform transform hover:scale-105 relative overflow-hidden border-4 border-transparent hover:border-red-600"
			>
				<div
					class="absolute inset-0 bg-gray-600 opacity-20 transition-opacity duration-300 group-hover:opacity-0"
				></div>
				<div class="relative z-10">
					<h3 class="text-2xl font-semibold mb-4">Buy Now</h3>
					<p class="text-lg mb-6">
						Upgrade to the full version for even more features and premium support. Unlock the full
						potential of Vocabulizer.
					</p>
					<a
						href="/buy"
						class="bg-red-500 text-white py-3 px-8 rounded-full text-lg font-semibold inline-flex items-center space-x-3 hover:bg-red-700 transition-all duration-300 shadow-lg transform hover:scale-105 active:scale-95"
					>
						<Icon src={ShoppingCart} class="w-6 h-6" />
						<span class="ml-2">Buy Now</span>
					</a>
				</div>
			</div>
		</div>
	</main>

	<!-- Footer -->
	<footer class="w-full py-8 mt-auto bg-gray-900 text-center">
		<p class="text-sm">© 2024 Vocabulizer. All Rights Reserved.</p>
		<nav class="flex justify-center space-x-4 text-sm mt-4">
			<a href="/terms" class="hover:underline">Terms</a>
			<a href="/privacy" class="hover:underline">Privacy</a>
			<a href="/contact" class="hover:underline">Contact</a>
		</nav>
	</footer>
</div>
