<script>
	import '../app.css';
	import { page } from '$app/stores';
</script>

<div
	class="min-h-screen flex flex-col items-center justify-center bg-gradient-to-br from-gray-800 to-gray-900 text-white"
>
	<h1 class="text-9xl font-extrabold mb-4 text-red-500">404</h1>
	<h1>{$page.status}: {$page.error.message}</h1>
	<a
		href="/"
		class="mt-6 bg-red-500 text-white py-2 px-6 rounded-full text-lg font-semibold hover:bg-red-600 transition-all duration-300"
	>
		Go Back Home
	</a>
</div>
