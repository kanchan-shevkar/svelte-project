<script>
	// No script needed for a basic contact page
</script>

<main class="font-sans leading-relaxed">
	<section class="bg-gradient-to-r from-purple-500 to-pink-500 text-white py-16 px-8 text-center">
		<h1 class="text-4xl md:text-5xl font-bold mb-4">Contact Us</h1>
		<p class="text-xl mb-8">Get in touch with our team. We'd love to hear from you!</p>
	</section>

	<section class="py-16 px-8 max-w-4xl mx-auto">
		<div class="grid grid-cols-1 md:grid-cols-2 gap-12">
			<div>
				<h2 class="text-3xl font-bold mb-8">Send us a message</h2>
				<form class="space-y-6">
					<div>
						<label for="name" class="block text-sm font-medium text-gray-700 mb-2">Name</label>
						<input type="text" id="name" name="name" class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-purple-500 focus:border-transparent">
					</div>
					<div>
						<label for="email" class="block text-sm font-medium text-gray-700 mb-2">Email</label>
						<input type="email" id="email" name="email" class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-purple-500 focus:border-transparent">
					</div>
					<div>
						<label for="message" class="block text-sm font-medium text-gray-700 mb-2">Message</label>
						<textarea id="message" name="message" rows="4" class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-purple-500 focus:border-transparent"></textarea>
					</div>
					<button type="submit" class="bg-purple-500 hover:bg-purple-600 text-white font-semibold py-3 px-6 rounded-lg transition duration-300">Send Message</button>
				</form>
			</div>

			<div>
				<h2 class="text-3xl font-bold mb-8">Get in touch</h2>
				<div class="space-y-6">
					<div class="flex items-start">
						<div class="flex-shrink-0">
							<svg class="h-6 w-6 text-purple-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
								<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/>
								<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/>
							</svg>
						</div>
						<div class="ml-3">
							<p class="text-lg font-medium text-gray-900">Address</p>
							<p class="text-gray-600">123 Web Dev Street<br>Tech City, TC 12345</p>
						</div>
					</div>

					<div class="flex items-start">
						<div class="flex-shrink-0">
							<svg class="h-6 w-6 text-purple-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
								<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/>
							</svg>
						</div>
						<div class="ml-3">
							<p class="text-lg font-medium text-gray-900">Phone</p>
							<p class="text-gray-600">(555) 123-4567</p>
						</div>
					</div>

					<div class="flex items-start">
						<div class="flex-shrink-0">
							<svg class="h-6 w-6 text-purple-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
								<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 4.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/>
							</svg>
						</div>
						<div class="ml-3">
							<p class="text-lg font-medium text-gray-900">Email</p>
							<p class="text-gray-600">hello@svelteapp.com</p>
						</div>
					</div>
				</div>
			</div>
		</div>
	</section>
</main>
