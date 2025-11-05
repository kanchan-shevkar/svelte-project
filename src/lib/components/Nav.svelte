<script>
	import { Link } from 'svelte-routing';
</script>

<nav class="bg-white shadow-lg">
	<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
		<div class="flex justify-between h-16">
			<div class="flex">
				<div class="flex-shrink-0 flex items-center">
					<h1 class="text-xl font-bold text-gray-800">My Svelte App</h1>
				</div>
				<div class="hidden sm:ml-6 sm:flex sm:space-x-8">
					<Link to="/" class="border-transparent text-gray-500 hover:border-gray-300 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium">
						Home
					</Link>
					<Link to="/about" class="border-transparent text-gray-500 hover:border-gray-300 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium">
						About
					</Link>
					<Link to="/contact" class="border-transparent text-gray-500 hover:border-gray-300 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium">
						Contact
					</Link>
				</div>
			</div>
		</div>
	</div>

	<!-- Mobile menu -->
	<div class="sm:hidden">
		<div class="pt-2 pb-3 space-y-1">
			<Link to="/" class="bg-indigo-50 border-indigo-500 text-indigo-700 block pl-3 pr-4 py-2 border-l-4 text-base font-medium">
				Home
			</Link>
			<Link to="/about" class="border-transparent text-gray-500 hover:bg-gray-50 hover:border-gray-300 hover:text-gray-700 block pl-3 pr-4 py-2 border-l-4 text-base font-medium">
				About
			</Link>
			<Link to="/contact" class="border-transparent text-gray-500 hover:bg-gray-50 hover:border-gray-300 hover:text-gray-700 block pl-3 pr-4 py-2 border-l-4 text-base font-medium">
				Contact
			</Link>
		</div>
	</div>
</nav>
