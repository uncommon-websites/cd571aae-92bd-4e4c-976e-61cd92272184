<script lang="ts">
	import "../app.css";
</script>

<div class="flex min-h-screen flex-col font-sans text-gray-900 selection:bg-ellis-green-200 selection:text-ellis-green-900">
	<header class="sticky top-0 z-50 w-full bg-white/80 backdrop-blur-md border-b border-gray-100">
		<div class="mx-auto flex h-20 max-w-[1400px] items-center justify-between px-6 lg:px-12">
			<!-- Logo -->
			<a href="/" class="flex items-center gap-2">
				<svg width="40" height="20" viewBox="0 0 40 20" fill="none" xmlns="http://www.w3.org/2000/svg" class="h-6 w-auto">
					<path d="M5.5 15.5C5.5 15.5 5.5 11.5 5.5 9.5C5.5 7.5 7 6 9 6H11" stroke="currentColor" stroke-width="2" stroke-linecap="round"/>
					<path d="M14 15.5V6" stroke="currentColor" stroke-width="2" stroke-linecap="round"/>
					<path d="M18 15.5V6" stroke="currentColor" stroke-width="2" stroke-linecap="round"/>
					<path d="M22 15.5V9.5" stroke="currentColor" stroke-width="2" stroke-linecap="round"/>
					<path d="M22 6V7" stroke="currentColor" stroke-width="2" stroke-linecap="round"/>
					<path d="M26 15.5C26 15.5 29 15.5 29 13.5C29 11.5 26 11.5 26 11.5C26 11.5 29 11.5 29 9.5C29 7.5 26 7.5 26 7.5" stroke="currentColor" stroke-width="2" stroke-linecap="round"/>
				</svg>
				<span class="font-serif text-2xl font-medium tracking-tight">ellis</span>
			</a>

			<!-- Navigation -->
			<nav class="hidden md:flex items-center gap-8 text-sm font-medium text-gray-600">
				<a href="/" class="text-gray-900">Home</a>
				<button class="flex items-center gap-1 hover:text-gray-900">
					Services
					<svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m6 9 6 6 6-6"/></svg>
				</button>
				<a href="/pricing" class="hover:text-gray-900">Pricing</a>
				<a href="/about" class="hover:text-gray-900">About</a>
				<a href="/resources" class="hover:text-gray-900">Resources</a>
			</nav>

			<!-- Actions -->
			<div class="flex items-center gap-6">
				<a href="/login" class="text-sm font-medium text-gray-600 hover:text-gray-900">Login</a>
				<a href="/schedule" class="group flex items-center gap-2 rounded-full border border-gray-200 bg-white pl-4 pr-1 py-1 text-xs font-semibold uppercase tracking-wider text-gray-900 transition-colors hover:border-gray-300 hover:bg-gray-50">
					SCHEDULE A CALL
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
				<div class="lg:col-span-4 flex flex-col gap-8">
					<a href="/" class="flex items-center gap-2">
						<span class="font-serif text-3xl font-medium tracking-tight">ellis</span>
					</a>
					<p class="text-xs text-gray-500 leading-relaxed max-w-sm">
						Ellis Legal, P.C. is a California-licensed law firm. The information provided here is for general informational purposes only and does not constitute legal advice. Viewing this information or contacting us through this website does not create an attorney-client relationship. For personalized legal advice, please reach out to us directly to setup a legal consult or consult directly with a qualified attorney.
					</p>
					<div class="text-xs text-gray-400 mt-auto">
						© 2025 Ellis Legal <span class="mx-2">|</span> <a href="#" class="hover:text-gray-600">Privacy Policy</a> <span class="mx-2">|</span> <a href="#" class="hover:text-gray-600">Terms of Use</a>
					</div>
				</div>

				<!-- Links Columns -->
				<div class="lg:col-span-2">
					<h4 class="text-xs font-semibold uppercase tracking-widest text-gray-400 mb-6">Menu</h4>
					<ul class="flex flex-col gap-3 text-sm font-medium text-gray-900">
						<li><a href="#" class="hover:text-ellis-green-600">Home</a></li>
						<li><a href="#" class="hover:text-ellis-green-600">Services</a></li>
						<li><a href="#" class="hover:text-ellis-green-600">Pricing</a></li>
						<li><a href="#" class="hover:text-ellis-green-600">About</a></li>
						<li><a href="#" class="hover:text-ellis-green-600">Resources</a></li>
					</ul>
				</div>

				<div class="lg:col-span-2">
					<h4 class="text-xs font-semibold uppercase tracking-widest text-gray-400 mb-6">Visa Options</h4>
					<ul class="flex flex-col gap-3 text-sm font-medium text-gray-900">
						<li><a href="#" class="hover:text-ellis-green-600">H-1B</a></li>
						<li><a href="#" class="hover:text-ellis-green-600">H-1B1</a></li>
						<li><a href="#" class="hover:text-ellis-green-600">TN</a></li>
						<li><a href="#" class="hover:text-ellis-green-600">O-1</a></li>
						<li><a href="#" class="hover:text-ellis-green-600">L-1</a></li>
						<li><a href="#" class="hover:text-ellis-green-600">J-1</a></li>
						<li><a href="#" class="hover:text-ellis-green-600">E-1/E-2</a></li>
						<li><a href="#" class="hover:text-ellis-green-600">E-3</a></li>
					</ul>
				</div>

				<div class="lg:col-span-2">
					<h4 class="text-xs font-semibold uppercase tracking-widest text-gray-400 mb-6">Green Card Options</h4>
					<ul class="flex flex-col gap-3 text-sm font-medium text-gray-900">
						<li><a href="#" class="hover:text-ellis-green-600">EB-1A</a></li>
						<li><a href="#" class="hover:text-ellis-green-600">EB-2 NIW</a></li>
						<li><a href="#" class="hover:text-ellis-green-600">EB-2 PERM</a></li>
						<li><a href="#" class="hover:text-ellis-green-600">EB-3 PERM</a></li>
					</ul>
				</div>

				<div class="lg:col-span-2">
					<div class="mb-12">
						<h4 class="text-xs font-semibold uppercase tracking-widest text-gray-400 mb-6">Other</h4>
						<ul class="flex flex-col gap-3 text-sm font-medium text-gray-900">
							<li><a href="#" class="hover:text-ellis-green-600">Naturalization</a></li>
						</ul>
					</div>
					<div>
						<h4 class="text-xs font-semibold uppercase tracking-widest text-gray-400 mb-6">Socials</h4>
						<ul class="flex flex-col gap-3 text-sm font-medium text-gray-900">
							<li><a href="#" class="hover:text-ellis-green-600">LinkedIn</a></li>
							<li><a href="#" class="hover:text-ellis-green-600">Instagram</a></li>
							<li><a href="#" class="hover:text-ellis-green-600">X</a></li>
						</ul>
					</div>
				</div>
			</div>
			
			<div class="flex justify-end border-t border-gray-200 pt-8">
				<div class="flex flex-col items-end gap-4">
					<span class="text-xs font-semibold uppercase tracking-widest text-gray-400">Schedule an appointment</span>
					<a href="/schedule" class="group flex items-center gap-2 rounded-full bg-gray-100 pl-6 pr-1 py-1 text-xs font-bold uppercase tracking-wider text-gray-900 transition-colors hover:bg-gray-200">
						GET IN TOUCH
						<div class="flex h-8 w-8 items-center justify-center rounded-full bg-ellis-green-300 text-gray-900 transition-colors group-hover:bg-ellis-green-400">
							<svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
						</div>
					</a>
				</div>
			</div>
		</div>
	</footer>
</div>
