<script>
	import Navbar from '../../components/Navbar.svelte';
	import { Icon, ArrowDown } from 'svelte-hero-icons';
</script>

<div
	class="min-h-screen flex flex-col items-center justify-center bg-gradient-to-br from-gray-800 to-gray-900 text-white"
>
	<Navbar />

	<header class="w-full mt-16 py-6 text-center border-b border-gray-700">
		<h1 class="text-7xl font-extrabold mb-4 text-red-500 tracking-wide">Vocabulizer</h1>
		<p class="text-xl font-light tracking-wider">Smart tool for unlocking language mastery</p>
	</header>
	<main class="flex flex-col items-center px-6 py-12 max-w-4xl text-center space-y-12">
		<h2 class="text-4xl font-bold mb-6">Download</h2>
		<p class="text-lg mb-12 leading-relaxed">
			Download the latest version of Vocabulizer to start enhancing your language learning journey.
			Simply click the button below to get started.
		</p>

		<!-- Download Options -->
		<div class="flex flex-col items-center space-y-12 w-full max-w-2xl">
			<!-- macOS -->
			<div class="w-full max-w-md">
				<div class="flex items-center mb-6">
					<hr class="border-gray-600 border-t-4 w-full" />
					<img src="/macos.svg" alt="macOS Icon" class="w-14 h-14 ml-6" />
				</div>
				<h3 class="text-2xl font-semibold mb-4">macOS</h3>
				<p class="text-lg mb-4 font-medium text-gray-400">
					For macOS, compatible with Apple Silicon (aarch64) and Intel (x64) architectures.
				</p>
				<div class="space-y-4">
					<a
						href="/download/Vocabulizer_0.1.3_aarch64.dmg"
						class="bg-red-500 text-white py-3 px-6 rounded-lg text-md font-medium inline-flex items-center space-x-2 hover:bg-red-600 transition-all duration-300 shadow-lg transform hover:scale-105 active:scale-95 w-full justify-center"
					>
						<Icon src={ArrowDown} class="w-5 h-5 text-white" />
						<span class="ml-2">Download macOS (aarch64)</span>
					</a>
					<a
						href="/download/Vocabulizer_0.1.3_x64.dmg"
						class="bg-red-500 text-white py-3 px-6 rounded-lg text-md font-medium inline-flex items-center space-x-2 hover:bg-red-600 transition-all duration-300 shadow-lg transform hover:scale-105 active:scale-95 w-full justify-center"
					>
						<Icon src={ArrowDown} class="w-5 h-5 text-white" />
						<span class="ml-2">Download macOS (x64)</span>
					</a>
				</div>
			</div>

			<!-- Windows -->
			<div class="w-full max-w-md">
				<div class="flex items-center mb-6">
					<hr class="border-gray-600 border-t-4 w-full" />
					<img src="/windows.svg" alt="Windows Icon" class="w-14 h-14 ml-6" />
				</div>
				<h3 class="text-2xl font-semibold mb-4">Windows</h3>
				<p class="text-lg mb-4 font-medium text-gray-400">
					For Windows 10/11. Choose between the installer or the MSI package.
				</p>
				<div class="space-y-4">
					<a
						href="/download/Vocabulizer_0.1.3_x64-setup.exe"
						class="bg-red-500 text-white py-3 px-6 rounded-lg text-md font-medium inline-flex items-center space-x-2 hover:bg-red-600 transition-all duration-300 shadow-lg transform hover:scale-105 active:scale-95 w-full justify-center"
					>
						<Icon src={ArrowDown} class="w-5 h-5 text-white" />
						<span class="ml-2">Download EXE</span>
					</a>
					<a
						href="/download/Vocabulizer_0.1.3_x64_en-US.msi"
						class="bg-red-500 text-white py-3 px-6 rounded-lg text-md font-medium inline-flex items-center space-x-2 hover:bg-red-600 transition-all duration-300 shadow-lg transform hover:scale-105 active:scale-95 w-full justify-center"
					>
						<Icon src={ArrowDown} class="w-5 h-5 text-white" />
						<span class="ml-2">Download MSI</span>
					</a>
				</div>
			</div>

			<!-- Linux -->
			<div class="w-full max-w-md">
				<div class="flex items-center mb-6">
					<hr class="border-gray-600 border-t-4 w-full" />
					<img src="/linux.svg" alt="Linux Icon" class="w-14 h-14 ml-6" />
				</div>
				<h3 class="text-2xl font-semibold mb-4">Linux</h3>
				<p class="text-lg mb-4 font-medium text-gray-400">
					For Linux distributions. Choose your preferred package format.
				</p>
				<div class="space-y-4">
					<a
						href="/download/vocabulizer-0.1.3-1.x86_64.rpm"
						class="bg-red-500 text-white py-3 px-6 rounded-lg text-md font-medium inline-flex items-center space-x-2 hover:bg-red-600 transition-all duration-300 shadow-lg transform hover:scale-105 active:scale-95 w-full justify-center"
					>
						<Icon src={ArrowDown} class="w-5 h-5 text-white" />
						<span class="ml-2">Download RPM</span>
					</a>
					<a
						href="/download/vocabulizer_0.1.3_amd64.AppImage"
						class="bg-red-500 text-white py-3 px-6 rounded-lg text-md font-medium inline-flex items-center space-x-2 hover:bg-red-600 transition-all duration-300 shadow-lg transform hover:scale-105 active:scale-95 w-full justify-center"
					>
						<Icon src={ArrowDown} class="w-5 h-5 text-white" />
						<span class="ml-2">Download AppImage</span>
					</a>
					<a
						href="/download/vocabulizer_0.1.3_amd64.deb"
						class="bg-red-500 text-white py-3 px-6 rounded-lg text-md font-medium inline-flex items-center space-x-2 hover:bg-red-600 transition-all duration-300 shadow-lg transform hover:scale-105 active:scale-95 w-full justify-center"
					>
						<Icon src={ArrowDown} class="w-5 h-5 text-white" />
						<span class="ml-2">Download DEB</span>
					</a>
					<a
						href="/download/Vocabulizer_aarch64.app.tar.gz"
						class="bg-red-500 text-white py-3 px-6 rounded-lg text-md font-medium inline-flex items-center space-x-2 hover:bg-red-600 transition-all duration-300 shadow-lg transform hover:scale-105 active:scale-95 w-full justify-center"
					>
						<Icon src={ArrowDown} class="w-5 h-5 text-white" />
						<span class="ml-2">Download TAR.GZ (aarch64)</span>
					</a>
					<a
						href="/download/Vocabulizer_x64.app.tar.gz"
						class="bg-red-500 text-white py-3 px-6 rounded-lg text-md font-medium inline-flex items-center space-x-2 hover:bg-red-600 transition-all duration-300 shadow-lg transform hover:scale-105 active:scale-95 w-full justify-center"
					>
						<Icon src={ArrowDown} class="w-5 h-5 text-white" />
						<span class="ml-2">Download TAR.GZ (x64)</span>
					</a>
				</div>
			</div>
		</div>
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
