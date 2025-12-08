<script lang="ts">
	let activeTab = $state('law-firm');
	let openFaq = $state(0);

	const faqs = [
		{
			question: "What makes Ellis different from traditional immigration law firms?",
			answer: "Ellis is what immigration would look like if your favorite tech company built it. Every case runs through structured workflows, automated checks, and a modern platform that gives you full visibility. And unlike software alone, nothing is ever finalized without human attorney review—so you get the speed and precision of technology with the experience and accountability of expert legal counsel."
		},
		{
			question: "How does Ellis use AI?",
			answer: "We use AI to streamline data entry, draft initial documents, and spot potential issues, allowing our attorneys to focus on high-value strategy and review."
		},
		{
			question: "Can you take over our existing immigration cases?",
			answer: "Yes, we have a dedicated transition team that makes moving your cases to Ellis seamless and efficient."
		},
		{
			question: "What types of companies does Ellis work with?",
			answer: "We work with companies of all sizes, from early-stage startups to Fortune 500 enterprises across various industries."
		},
		{
			question: "Do you work with founders?",
			answer: "Absolutely. We specialize in O-1 and EB-1 visas for founders and have helped hundreds of entrepreneurs establish themselves in the U.S."
		}
	];
</script>

<div class="flex flex-col">
	<!-- Hero Section -->
	<section class="relative overflow-hidden bg-gray-50 pt-12 pb-24 lg:pt-24 lg:pb-32">
		<div class="mx-auto max-w-[1400px] px-6 lg:px-12">
			<div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
				<!-- Hero Image (Left) -->
				<div class="relative h-[600px] w-full rounded-2xl overflow-hidden bg-ellis-green-100/50">
					<!-- Abstract representation of the statue -->
					<div class="absolute inset-0 bg-[url('https://images.unsplash.com/photo-1550100136-e074fa714874?q=80&w=800&auto=format&fit=crop')] bg-cover bg-center opacity-80 mix-blend-multiply grayscale contrast-125 sepia-[.3] hue-rotate-[130deg]"></div>
					<div class="absolute inset-0 bg-gradient-to-t from-gray-50 via-transparent to-transparent"></div>
				</div>

				<!-- Hero Content (Right) -->
				<div class="flex flex-col gap-12 pl-0 lg:pl-12">
					<div class="flex flex-col gap-6">
						<span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-400">First Ever Immigration Platform</span>
						<h1 class="font-serif text-6xl lg:text-7xl leading-[1.1] text-gray-900">
							U.S. Immigration<br> Solved for<br> People Teams
						</h1>
					</div>

					<div class="grid grid-cols-[100px_1fr] gap-8 border-t border-gray-200 pt-8">
						<span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-400 mt-1">Our Promise</span>
						<p class="text-sm leading-relaxed text-gray-600 max-w-sm">
							We ensure your international hires arrive on-time, stay compliant, and feel valued from Day 1.
						</p>
					</div>

					<div class="grid grid-cols-[100px_1fr] gap-8 border-t border-gray-200 pt-8">
						<span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-400 mt-3">Get In Touch</span>
						<a href="/schedule" class="w-fit group flex items-center gap-2 rounded-full bg-black pl-6 pr-1 py-1 text-xs font-bold uppercase tracking-wider text-white transition-colors hover:bg-gray-800">
							SCHEDULE A CALL
							<div class="flex h-8 w-8 items-center justify-center rounded-full bg-ellis-green-300 text-gray-900 transition-colors group-hover:bg-ellis-green-400">
								<svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
							</div>
						</a>
					</div>
				</div>
			</div>
		</div>
	</section>

	<!-- Intro Section -->
	<section class="py-24 bg-white">
		<div class="mx-auto max-w-[1400px] px-6 lg:px-12">
			<div class="flex justify-between items-baseline border-b border-gray-200 pb-4 mb-12">
				<span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-900">What We Do</span>
				<span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-900">U.S. Immigration Solved</span>
			</div>

			<div class="max-w-4xl">
				<h2 class="font-serif text-5xl lg:text-6xl leading-[1.1] text-gray-900 mb-8">
					Ellis is a modern immigration law firm. <span class="text-gray-400">We combine world-class legal expertise with best-in-class technology to deliver a completely reimagined immigration experience.</span>
				</h2>
			</div>

			<div class="mt-24 flex items-center gap-12 border-t border-gray-200 pt-8">
				<span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-400">Trusted By</span>
				<div class="flex items-center gap-12 opacity-50 grayscale">
					<!-- Logos (Placeholders text for now as I don't have SVGs) -->
					<span class="font-bold text-xl font-serif">Adaptive</span>
					<span class="font-bold text-xl">wordware</span>
					<span class="font-bold text-xl tracking-tighter">micro1.</span>
					<span class="font-bold text-xl flex items-center gap-1">Trustwell <div class="h-2 w-2 bg-black rounded-full"></div></span>
				</div>
			</div>
		</div>
	</section>

	<!-- Split Feature Section -->
	<section class="py-24 bg-white">
		<div class="mx-auto max-w-[1400px] px-6 lg:px-12">
			<div class="grid grid-cols-1 lg:grid-cols-2 gap-24">
				<div class="flex flex-col justify-between h-full">
					<div class="flex flex-col gap-4">
						<button class="text-left font-serif text-6xl text-gray-900 italic hover:opacity-80 transition-opacity">
							<span class="text-ellis-green-500 mr-4">*</span>Law Firm
						</button>
						<button class="text-left font-sans text-6xl text-gray-300 hover:text-gray-400 transition-colors">
							Platform
						</button>
					</div>
					
					<div class="mt-auto pt-12">
						<div class="flex gap-4 text-xs font-bold text-gray-300 mb-8">
							<span class="text-gray-900">01</span>
							<span>02</span>
						</div>
						<p class="text-lg text-gray-600 max-w-md leading-relaxed">
							Our attorneys have scaled immigration programs for companies of all sizes, single founder startups to Fortune 500s.
						</p>
					</div>
				</div>

				<div class="relative h-[600px] bg-gray-100 rounded-lg overflow-hidden">
					<img src="https://images.unsplash.com/photo-1556761175-5973dc0f32e7?q=80&w=1000&auto=format&fit=crop" alt="Team working" class="absolute inset-0 h-full w-full object-cover grayscale contrast-75 sepia-[.2]" />
				</div>
			</div>
		</div>
	</section>

	<!-- Platform Grid Section -->
	<section class="py-24 bg-white">
		<div class="mx-auto max-w-[1400px] px-6 lg:px-12">
			<div class="flex justify-between items-baseline border-b border-gray-200 pb-4 mb-12">
				<span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-900">Our Platform</span>
				<span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-900">All-In-One Solution</span>
			</div>

			<h2 class="font-serif text-5xl lg:text-6xl leading-[1.1] text-gray-900 mb-24 max-w-4xl">
				Centralize your global mobility program so your team can move <span class="italic">faster</span> and stay compliant, with total visibility and peace of mind.
			</h2>

			<div class="grid grid-cols-1 md:grid-cols-2 gap-8">
				<!-- Card 1: Track -->
				<div class="bg-gray-50 rounded-xl p-8 flex flex-col gap-8">
					<h3 class="font-serif text-2xl">Track</h3>
					<div class="grid grid-cols-[80px_1fr] gap-8">
						<span class="text-[10px] font-bold uppercase tracking-widest text-gray-400 mt-1">Up To Date</span>
						<p class="text-sm text-gray-600 leading-relaxed">
							Real-time visibility into every step from internal review to post-filing updates—through direct USCIS integration.
						</p>
					</div>
					<div class="mt-auto bg-white rounded-lg p-6 shadow-sm border border-gray-100 flex items-center justify-center h-48">
						<div class="w-full max-w-[200px] space-y-2">
							<div class="h-1 w-full bg-gray-100 rounded-full overflow-hidden">
								<div class="h-full w-2/3 bg-gray-900 rounded-full"></div>
							</div>
							<div class="flex justify-between text-[10px] font-medium text-gray-500">
								<span>USCIS PROCESSING</span>
							</div>
						</div>
					</div>
				</div>

				<!-- Card 2: Vault -->
				<div class="bg-gray-50 rounded-xl p-8 flex flex-col gap-8">
					<h3 class="font-serif text-2xl">Vault</h3>
					<div class="grid grid-cols-[80px_1fr] gap-8">
						<span class="text-[10px] font-bold uppercase tracking-widest text-gray-400 mt-1">Fully Secure</span>
						<p class="text-sm text-gray-600 leading-relaxed">
							Securely store all immigration documents, petitions, and approvals for every employee.
						</p>
					</div>
					<div class="mt-auto bg-white rounded-lg p-6 shadow-sm border border-gray-100 flex items-center justify-center h-48">
						<div class="flex flex-col items-center gap-3">
							<div class="h-10 w-10 rounded-full border-2 border-gray-200 border-t-gray-900 animate-spin"></div>
							<span class="text-xs font-medium text-gray-900">Processing Document</span>
							<span class="text-[10px] text-gray-400 uppercase tracking-wider">VISA-STAMP.JPG</span>
						</div>
					</div>
				</div>

				<!-- Card 3: Radar -->
				<div class="bg-gray-50 rounded-xl p-8 flex flex-col gap-8">
					<h3 class="font-serif text-2xl">Radar</h3>
					<div class="grid grid-cols-[80px_1fr] gap-8">
						<span class="text-[10px] font-bold uppercase tracking-widest text-gray-400 mt-1">You're Covered</span>
						<p class="text-sm text-gray-600 leading-relaxed">
							Automatic alerts for renewals, expirations, and deadlines—so nothing falls through the cracks.
						</p>
					</div>
					<div class="mt-auto bg-white rounded-lg p-6 shadow-sm border border-gray-100 flex items-center justify-center h-48 relative overflow-hidden">
						<div class="absolute inset-0 flex items-center justify-center opacity-50 blur-[1px]">
							<!-- Fake ID Card -->
							<div class="w-48 h-28 bg-gray-100 rounded border border-gray-200 p-2 flex gap-2">
								<div class="w-8 h-10 bg-gray-300 rounded"></div>
								<div class="flex-1 space-y-1">
									<div class="h-2 w-20 bg-gray-300 rounded"></div>
									<div class="h-1 w-full bg-gray-200 rounded"></div>
									<div class="h-1 w-full bg-gray-200 rounded"></div>
								</div>
							</div>
						</div>
						<div class="relative z-10 bg-white px-3 py-1 rounded shadow text-xs font-bold text-red-500 flex items-center gap-2">
							<div class="h-2 w-2 bg-red-500 rounded-full"></div>
							Expiring Soon
						</div>
					</div>
				</div>

				<!-- Card 4: Ellis AI -->
				<div class="bg-gray-50 rounded-xl p-8 flex flex-col gap-8">
					<h3 class="font-serif text-2xl">Ellis AI</h3>
					<div class="grid grid-cols-[80px_1fr] gap-8">
						<span class="text-[10px] font-bold uppercase tracking-widest text-gray-400 mt-1">Just Ask</span>
						<p class="text-sm text-gray-600 leading-relaxed">
							Instantly surface answers like "What's the status of David's H-1B?" or "Show me who needs renewals in Q4."
						</p>
					</div>
					<div class="mt-auto bg-white rounded-lg p-6 shadow-sm border border-gray-100 flex items-center justify-center h-48">
						<div class="w-full bg-gray-50 rounded-full px-4 py-2 flex justify-between items-center border border-gray-200">
							<span class="text-xs text-gray-500">Ask Ellis AI...</span>
							<div class="h-6 w-6 rounded-full bg-gray-200 flex items-center justify-center">
								<svg width="10" height="10" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
							</div>
						</div>
					</div>
				</div>
			</div>

			<div class="mt-24 grid grid-cols-[100px_1fr] gap-8 border-t border-gray-200 pt-8">
				<span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-400 mt-3">Demo</span>
				<div class="flex flex-col gap-8">
					<h3 class="font-serif text-2xl">Want to see it in action?</h3>
					<p class="text-sm text-gray-600 leading-relaxed max-w-lg">
						Schedule a personalized demo to see how Ellis can transform your immigration process. We'll show you exactly how our platform works and answer any questions about your specific needs.
					</p>
					<a href="/schedule" class="group flex items-center gap-2 text-xs font-bold uppercase tracking-wider text-gray-900">
						SCHEDULE A CALL
						<div class="flex h-6 w-6 items-center justify-center rounded-full bg-ellis-green-300 text-gray-900 transition-colors group-hover:bg-ellis-green-400">
							<svg width="10" height="10" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
						</div>
					</a>
				</div>
			</div>
		</div>
	</section>

	<!-- Testimonials Section -->
	<section class="py-24 bg-white">
		<div class="mx-auto max-w-[1400px] px-6 lg:px-12">
			<div class="flex justify-between items-baseline border-b border-gray-200 pb-4 mb-12">
				<span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-900">How We Work</span>
				<span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-900">Your Immigration Team</span>
			</div>

			<h2 class="font-serif text-5xl lg:text-6xl leading-[1.1] text-gray-900 mb-24 max-w-4xl">
				We become an extension of your <span class="underline decoration-1 underline-offset-4 decoration-gray-300">team</span>, bringing deep immigration expertise and custom solutions tailored to your business.
			</h2>

			<div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
				<div class="relative h-[500px] bg-ellis-green-100/50 rounded-lg overflow-hidden">
					<!-- Stylized portrait placeholder -->
					<img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?q=80&w=800&auto=format&fit=crop" alt="Sean McDermott" class="absolute inset-0 h-full w-full object-cover mix-blend-multiply grayscale contrast-125" />
				</div>
				<div class="flex flex-col justify-between h-full py-8">
					<div class="flex justify-between items-baseline mb-12">
						<span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-900">Testimonials</span>
						<div class="flex gap-4 text-xs font-bold text-gray-300">
							<span class="text-gray-900">01</span>
							<span>02</span>
							<span>03</span>
						</div>
					</div>
					
					<blockquote class="font-sans text-xl lg:text-2xl leading-relaxed text-gray-600 mb-12">
						"Ellis is an exceptional immigration partner, delivering fast and knowledgeable service. Their platform makes the process easier than anything I've experienced in over a decade and a half of hiring international candidates to tech companies."
					</blockquote>

					<div>
						<p class="text-[10px] font-bold uppercase tracking-widest text-gray-900">Sean McDermott</p>
						<p class="text-[10px] font-bold uppercase tracking-widest text-gray-400 mt-1">Chief People Officer, Adaptive Security</p>
					</div>

					<div class="mt-12 h-0.5 w-full bg-gray-100">
						<div class="h-full w-1/3 bg-gray-900"></div>
					</div>
				</div>
			</div>
		</div>
	</section>

	<!-- FAQ Section -->
	<section class="py-24 bg-white">
		<div class="mx-auto max-w-[1400px] px-6 lg:px-12">
			<div class="grid grid-cols-1 lg:grid-cols-12 gap-12">
				<div class="lg:col-span-4 flex flex-col gap-8">
					<h2 class="font-serif text-5xl text-gray-900">Ellis FAQ</h2>
					<p class="text-sm text-gray-600">Got questions? We've got answers.</p>
					<a href="/schedule" class="group flex items-center gap-2 text-xs font-bold uppercase tracking-wider text-gray-900 mt-4">
						SCHEDULE A CALL
						<div class="flex h-6 w-6 items-center justify-center rounded-full bg-ellis-green-300 text-gray-900 transition-colors group-hover:bg-ellis-green-400">
							<svg width="10" height="10" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
						</div>
					</a>
				</div>

				<div class="lg:col-span-8">
					<div class="flex flex-col">
						{#each faqs as faq, i}
							<div class="border-b border-gray-200">
								<button 
									class="w-full py-8 flex items-center justify-between text-left group"
									onclick={() => openFaq = openFaq === i ? -1 : i}
								>
									<span class="text-sm font-medium text-gray-900 group-hover:text-gray-600 transition-colors pr-8">{faq.question}</span>
									<div class="flex-shrink-0 transition-transform duration-300 {openFaq === i ? 'rotate-45' : ''}">
										{#if openFaq === i}
											<div class="h-6 w-6 rounded-full bg-ellis-green-300 flex items-center justify-center text-gray-900">
												<svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 6 6 18"/><path d="m6 6 12 12"/></svg>
											</div>
										{:else}
											<svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 5v14"/><path d="M5 12h14"/></svg>
										{/if}
									</div>
								</button>
								{#if openFaq === i}
									<div class="pb-8 text-sm leading-relaxed text-gray-600 max-w-2xl">
										{faq.answer}
									</div>
								{/if}
							</div>
						{/each}
					</div>
				</div>
			</div>
		</div>
	</section>

	<!-- Footer CTA -->
	<section class="py-24 bg-white">
		<div class="mx-auto max-w-[1400px] px-6 lg:px-12">
			<div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
				<div class="relative h-[400px] w-full flex items-center justify-center">
					<!-- Torch illustration placeholder -->
					<div class="relative h-full w-full max-w-xs opacity-80">
						<div class="absolute inset-0 bg-ellis-green-100 opacity-50 blur-3xl rounded-full"></div>
						<img src="https://images.unsplash.com/photo-1550100136-e074fa714874?q=80&w=400&auto=format&fit=crop" alt="Torch" class="relative z-10 h-full w-full object-cover mask-image-torch mix-blend-multiply grayscale contrast-125 sepia-[.3] hue-rotate-[130deg] rounded-full" style="mask-image: linear-gradient(to bottom, black, transparent);" />
					</div>
				</div>

				<div class="flex flex-col gap-12">
					<div class="flex justify-between items-baseline border-b border-gray-200 pb-4">
						<span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-900">U.S. Immigration Solved</span>
					</div>

					<h2 class="font-serif text-5xl lg:text-6xl leading-[1.1] text-gray-900">
						Ready to modernize your immigration program?
					</h2>

					<div class="grid grid-cols-[100px_1fr] gap-8 border-t border-gray-200 pt-8">
						<span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-400 mt-3">What Now</span>
						<p class="text-sm leading-relaxed text-gray-600 max-w-sm">
							Let's discuss your immigration needs and build a solution that works.
						</p>
					</div>

					<div class="grid grid-cols-[100px_1fr] gap-8 border-t border-gray-200 pt-8">
						<span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-400 mt-3">Start Today</span>
						<a href="/schedule" class="w-fit group flex items-center gap-2 rounded-full bg-black pl-6 pr-1 py-1 text-xs font-bold uppercase tracking-wider text-white transition-colors hover:bg-gray-800">
							SCHEDULE A CALL
							<div class="flex h-8 w-8 items-center justify-center rounded-full bg-ellis-green-300 text-gray-900 transition-colors group-hover:bg-ellis-green-400">
								<svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
							</div>
						</a>
					</div>
				</div>
			</div>
		</div>
	</section>
</div>

<style>
	/* Custom mask for the torch image to make it look like it's fading out */
	.mask-image-torch {
		mask-image: linear-gradient(to bottom, rgba(0,0,0,1) 0%, rgba(0,0,0,0) 100%);
		-webkit-mask-image: linear-gradient(to bottom, rgba(0,0,0,1) 0%, rgba(0,0,0,0) 100%);
	}
</style>

