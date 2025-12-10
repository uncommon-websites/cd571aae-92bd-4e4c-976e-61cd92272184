<script lang="ts">
	import "../app.css";
</script>

<div class="flex min-h-screen flex-col font-sans text-gray-900 selection:bg-primary-200 selection:text-primary-900">
	<header class="sticky top-0 z-50 w-full bg-white/80 backdrop-blur-md border-b border-gray-100">
		<div class="mx-auto flex h-20 max-w-[1400px] items-center justify-between px-6 lg:px-12">
			<!-- Logo -->
			<a href="/" class="flex items-center gap-2">
				<svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="h-6 w-6">
					<path
						fill-rule="evenodd"
						clip-rule="evenodd"
						d="M12.2566 21.954C17.929 21.954 22.5274 17.484 22.5274 11.9699C22.5274 6.45586 17.929 1.98584 12.2566 1.98584C6.58422 1.98584 1.98584 6.45586 1.98584 11.9699C1.98584 17.484 6.58422 21.954 12.2566 21.954ZM15.4608 6.63684C15.6167 6.09831 15.0791 5.77985 14.5881 6.1199L7.73395 10.8665C7.20146 11.2352 7.28522 11.9699 7.85977 11.9699H9.66465V11.9563H13.1823L10.3161 12.9394L9.05251 17.303C8.89655 17.8415 9.43412 18.16 9.92517 17.8199L16.7793 13.0734C17.3118 12.7046 17.228 11.9699 16.6535 11.9699H13.9165L15.4608 6.63684Z"
						fill="currentColor"
					/>
				</svg>
				<span class="font-serif text-2xl font-medium tracking-tight">Crosby</span>
			</a>

			<!-- Navigation -->
			<nav class="hidden md:flex items-center gap-8 text-sm font-medium text-gray-600">
				<a href="/" class="text-gray-900">Home</a>
				<a href="/how-it-works" class="hover:text-gray-900">How It Works</a>
				<a href="/pricing" class="hover:text-gray-900">Pricing</a>
				<a href="/about" class="hover:text-gray-900">About</a>
				<a href="/careers" class="hover:text-gray-900">Careers</a>
			</nav>

			<!-- Actions -->
			<div class="flex items-center gap-6">
				<a href="mailto:team@crosby.ai" class="text-sm font-medium text-gray-600 hover:text-gray-900">Contact</a>
				<a href="mailto:team@crosby.ai" class="group flex items-center gap-2 rounded-full border border-gray-200 bg-white pl-4 pr-1 py-1 text-xs font-semibold uppercase tracking-wider text-gray-900 transition-colors hover:border-gray-300 hover:bg-gray-50">
					GET STARTED
					<div class="flex h-6 w-6 items-center justify-center rounded-full bg-gray-100 text-gray-900 transition-colors group-hover:bg-gray-200">
						<svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
					</div>
				</a>
			</div>
		</div>
	</header>

	<main class="flex-1">
		<slot />
	</main>

	<footer class="bg-gray-50 pt-24 pb-12">
		<div class="mx-auto max-w-[1400px] px-6 lg:px-12">
			<div class="grid grid-cols-1 lg:grid-cols-12 gap-12 lg:gap-8 mb-24">
				<!-- Brand Column -->
				<div class="lg:col-span-5 flex flex-col gap-8">
					<a href="/" class="flex items-center gap-2">
						<svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="h-6 w-6">
							<path
								fill-rule="evenodd"
								clip-rule="evenodd"
								d="M12.2566 21.954C17.929 21.954 22.5274 17.484 22.5274 11.9699C22.5274 6.45586 17.929 1.98584 12.2566 1.98584C6.58422 1.98584 1.98584 6.45586 1.98584 11.9699C1.98584 17.484 6.58422 21.954 12.2566 21.954ZM15.4608 6.63684C15.6167 6.09831 15.0791 5.77985 14.5881 6.1199L7.73395 10.8665C7.20146 11.2352 7.28522 11.9699 7.85977 11.9699H9.66465V11.9563H13.1823L10.3161 12.9394L9.05251 17.303C8.89655 17.8415 9.43412 18.16 9.92517 17.8199L16.7793 13.0734C17.3118 12.7046 17.228 11.9699 16.6535 11.9699H13.9165L15.4608 6.63684Z"
								fill="currentColor"
							/>
						</svg>
						<span class="font-serif text-3xl font-medium tracking-tight">Crosby</span>
					</a>
					<p class="text-xs text-gray-500 leading-relaxed max-w-sm">
						Crosby Legal PLLC is a law firm combining legal expertise with AI technology. The information provided here is for general informational purposes only and does not constitute legal advice. Viewing this information or contacting us through this website does not create an attorney-client relationship.
					</p>
					<div class="text-xs text-gray-400 mt-auto">
						© 2025 Crosby Legal <span class="mx-2">|</span> <a href="#" class="hover:text-gray-600">Privacy Policy</a> <span class="mx-2">|</span> <a href="#" class="hover:text-gray-600">Terms of Use</a>
					</div>
				</div>

				<!-- Links Columns -->
				<div class="lg:col-span-2">
					<h4 class="text-xs font-semibold uppercase tracking-widest text-gray-400 mb-6">Company</h4>
					<ul class="flex flex-col gap-3 text-sm font-medium text-gray-900">
						<li><a href="/" class="hover:text-primary-600">Home</a></li>
						<li><a href="/how-it-works" class="hover:text-primary-600">How It Works</a></li>
						<li><a href="/pricing" class="hover:text-primary-600">Pricing</a></li>
						<li><a href="/about" class="hover:text-primary-600">About</a></li>
						<li><a href="/careers" class="hover:text-primary-600">Careers</a></li>
					</ul>
				</div>

				<div class="lg:col-span-2">
					<h4 class="text-xs font-semibold uppercase tracking-widest text-gray-400 mb-6">Resources</h4>
					<ul class="flex flex-col gap-3 text-sm font-medium text-gray-900">
						<li><a href="#" class="hover:text-primary-600">Blog</a></li>
						<li><a href="#" class="hover:text-primary-600">Case Studies</a></li>
						<li><a href="#" class="hover:text-primary-600">Documentation</a></li>
						<li><a href="#" class="hover:text-primary-600">Support</a></li>
					</ul>
				</div>

				<div class="lg:col-span-3">
					<h4 class="text-xs font-semibold uppercase tracking-widest text-gray-400 mb-6">Contact</h4>
					<ul class="flex flex-col gap-3 text-sm font-medium text-gray-900">
						<li><a href="mailto:team@crosby.ai" class="hover:text-primary-600">team@crosby.ai</a></li>
						<li class="text-gray-500 mt-4">New York City</li>
					</ul>
					<div class="mt-8">
						<h4 class="text-xs font-semibold uppercase tracking-widest text-gray-400 mb-6">Follow Us</h4>
						<ul class="flex flex-col gap-3 text-sm font-medium text-gray-900">
							<li><a href="#" class="hover:text-primary-600">LinkedIn</a></li>
							<li><a href="#" class="hover:text-primary-600">Twitter</a></li>
						</ul>
					</div>
				</div>
			</div>
			
			<div class="flex justify-end border-t border-gray-200 pt-8">
				<div class="flex flex-col items-end gap-4">
					<span class="text-xs font-semibold uppercase tracking-widest text-gray-400">Ready to get started?</span>
					<a href="mailto:team@crosby.ai" class="group flex items-center gap-2 rounded-full bg-gray-100 pl-6 pr-1 py-1 text-xs font-bold uppercase tracking-wider text-gray-900 transition-colors hover:bg-gray-200">
						GET IN TOUCH
						<div class="flex h-8 w-8 items-center justify-center rounded-full bg-primary-300 text-gray-900 transition-colors group-hover:bg-primary-400">
							<svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
						</div>
					</a>
				</div>
			</div>
		</div>
	</footer>
</div>
