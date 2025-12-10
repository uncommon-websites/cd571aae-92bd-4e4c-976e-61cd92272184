<script lang="ts">
	let activeTab = $state('law-firm');
	let openFaq = $state(0);

	const faqs = [
		{
			question: "What makes Crosby different from traditional law firms?",
			answer: "Crosby is the first hybrid law firm combining legal practice with AI technology. We deliver contract reviews in under four hours through lawyer-supervised AI agents. Every contract is reviewed by barred attorneys with domain expertise, but our AI agents learn from each review to optimize for speed and reduce bottlenecks."
		},
		{
			question: "How does the 4-hour turnaround work?",
			answer: "90%+ of documents are returned within hours, with many reviews completed within minutes. We guarantee a 4-hour turnaround time. Our AI agents handle initial analysis and our attorneys provide expert review and final approval."
		},
		{
			question: "What types of contracts do you review?",
			answer: "We specialize in commercial contracts for fast-growing startups, including customer agreements, vendor contracts, partnership agreements, and more. Our market benchmarks help optimize terms that won't create deal bottlenecks."
		},
		{
			question: "How do you integrate with our workflow?",
			answer: "Crosby works via Slack, email, or CRM triggers. We fit into your existing workflow without requiring constant input—acting as an extension of your team."
		},
		{
			question: "Who are your typical customers?",
			answer: "We work with sales leaders and GTM teams at Series A+ fast-growing startups who need quick contract reviews to keep deals moving. Our customers include Cursor, Clay, Cartesia, Pocus, and many other high-growth companies."
		}
	];
</script>

<div class="flex flex-col">
	<!-- Hero Section -->
	<section class="relative overflow-hidden bg-gray-50 pt-12 pb-24 lg:pt-24 lg:pb-32">
		<div class="mx-auto max-w-[1400px] px-6 lg:px-12">
			<div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
				<!-- Hero Image (Left) -->
				<div class="relative h-[600px] w-full rounded-2xl overflow-hidden bg-gray-100">
					<img src="/generated/image-confident-sales-leader-at-modern-desk-re-1765401796063-0.webp" alt="Sales leader reviewing contracts" class="absolute inset-0 h-full w-full object-cover" />
					<div class="absolute inset-0 bg-gradient-to-t from-gray-50 via-transparent to-transparent"></div>
				</div>

				<!-- Hero Content (Right) -->
				<div class="flex flex-col gap-12 pl-0 lg:pl-12">
					<div class="flex flex-col gap-6">
						<span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-400">Contract Reviews in Hours</span>
						<h1 class="font-serif text-6xl lg:text-7xl leading-[1.1] text-gray-900">
							Legal Speed<br> Meets Sales<br> Velocity
						</h1>
					</div>

					<div class="grid grid-cols-[100px_1fr] gap-8 border-t border-gray-200 pt-8">
						<span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-400 mt-1">Our Promise</span>
						<p class="text-sm leading-relaxed text-gray-600 max-w-sm">
							Contract reviews in under four hours. Lawyer-supervised AI agents and market benchmarks that keep deals moving.
						</p>
					</div>

					<div class="grid grid-cols-[100px_1fr] gap-8 border-t border-gray-200 pt-8">
						<span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-400 mt-3">Get Started</span>
						<a href="mailto:team@crosby.ai" class="w-fit group flex items-center gap-2 rounded-full bg-black pl-6 pr-1 py-1 text-xs font-bold uppercase tracking-wider text-white transition-colors hover:bg-gray-800">
							CONTACT US
							<div class="flex h-8 w-8 items-center justify-center rounded-full bg-primary-300 text-gray-900 transition-colors group-hover:bg-primary-400">
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
				<span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-900">Contract Reviews Solved</span>
			</div>

			<div class="max-w-4xl">
				<h2 class="font-serif text-5xl lg:text-6xl leading-[1.1] text-gray-900 mb-8">
					Crosby is the first hybrid law firm combining legal practice with AI technology. <span class="text-gray-400">We deliver contract reviews in under four hours through lawyer-supervised AI agents and market benchmarks.</span>
				</h2>
			</div>

			<div class="mt-24 flex items-center gap-12 border-t border-gray-200 pt-8">
				<span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-400">Trusted By</span>
				<div class="flex items-center gap-12 opacity-50 grayscale">
					<!-- Customer logos -->
					<span class="font-bold text-xl">Cursor</span>
					<span class="font-bold text-xl">Clay</span>
					<span class="font-bold text-xl">Cartesia</span>
					<span class="font-bold text-xl">Pocus</span>
					<span class="font-bold text-xl">Pulley</span>
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
							<span class="text-primary-500 mr-4">*</span>Law Firm
						</button>
						<button class="text-left font-sans text-6xl text-gray-300 hover:text-gray-400 transition-colors">
							+ AI Agents
						</button>
					</div>
					
					<div class="mt-auto pt-12">
						<div class="flex gap-4 text-xs font-bold text-gray-300 mb-8">
							<span class="text-gray-900">01</span>
							<span>02</span>
						</div>
						<p class="text-lg text-gray-600 max-w-md leading-relaxed">
							Barred attorneys with domain expertise review every contract. AI agents learn from each review to optimize for redlines least likely to create bottlenecks.
						</p>
					</div>
				</div>

				<div class="relative h-[600px] bg-gray-100 rounded-lg overflow-hidden">
					<img src="/generated/image-diverse-team-of-lawyers-and-engineers-co-1765401799130-1.webp" alt="Legal and engineering team collaboration" class="absolute inset-0 h-full w-full object-cover" />
				</div>
			</div>
		</div>
	</section>

	<!-- Platform Grid Section -->
	<section class="py-24 bg-white">
		<div class="mx-auto max-w-[1400px] px-6 lg:px-12">
			<div class="flex justify-between items-baseline border-b border-gray-200 pb-4 mb-12">
				<span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-900">How It Works</span>
				<span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-900">Speed Meets Precision</span>
			</div>

			<h2 class="font-serif text-5xl lg:text-6xl leading-[1.1] text-gray-900 mb-24 max-w-4xl">
				Close deals <span class="italic">faster</span> with contract reviews that combine AI speed and attorney precision, delivered in hours not days.
			</h2>

			<div class="grid grid-cols-1 md:grid-cols-2 gap-8">
				<!-- Card 1: Lightning Fast -->
				<div class="bg-gray-50 rounded-xl p-8 flex flex-col gap-8">
					<h3 class="font-serif text-2xl">Lightning Fast</h3>
					<div class="grid grid-cols-[80px_1fr] gap-8">
						<span class="text-[10px] font-bold uppercase tracking-widest text-gray-400 mt-1">4-Hour SLA</span>
						<p class="text-sm text-gray-600 leading-relaxed">
							90%+ of documents returned within hours. Many reviews completed within minutes. Guaranteed 4-hour turnaround.
						</p>
					</div>
					<div class="mt-auto bg-white rounded-lg p-6 shadow-sm border border-gray-100 flex items-center justify-center h-48">
						<div class="flex flex-col items-center gap-3">
							<div class="text-5xl font-serif text-gray-900">4h</div>
							<span class="text-xs font-medium text-gray-500 uppercase tracking-wider">Guaranteed Turnaround</span>
						</div>
					</div>
				</div>

				<!-- Card 2: Market Benchmarks -->
				<div class="bg-gray-50 rounded-xl p-8 flex flex-col gap-8">
					<h3 class="font-serif text-2xl">Market Benchmarks</h3>
					<div class="grid grid-cols-[80px_1fr] gap-8">
						<span class="text-[10px] font-bold uppercase tracking-widest text-gray-400 mt-1">Data-Driven</span>
						<p class="text-sm text-gray-600 leading-relaxed">
							Agents optimize for redlines least likely to create bottlenecks, informed by market data from hundreds of deals.
						</p>
					</div>
					<div class="mt-auto bg-white rounded-lg p-6 shadow-sm border border-gray-100 flex items-center justify-center h-48">
						<div class="flex flex-col items-center gap-3">
							<div class="flex items-baseline gap-1">
								<span class="text-4xl font-serif text-gray-900">80%</span>
								<span class="text-sm text-gray-500">faster</span>
							</div>
							<span class="text-xs font-medium text-gray-500 uppercase tracking-wider">Redline Speed</span>
						</div>
					</div>
				</div>

				<!-- Card 3: Knowledge Agents -->
				<div class="bg-gray-50 rounded-xl p-8 flex flex-col gap-8">
					<h3 class="font-serif text-2xl">Knowledge Agents</h3>
					<div class="grid grid-cols-[80px_1fr] gap-8">
						<span class="text-[10px] font-bold uppercase tracking-widest text-gray-400 mt-1">Always Learning</span>
						<p class="text-sm text-gray-600 leading-relaxed">
							Legal agents learn from each review, storing client information and preferences for consistent, intelligent reviews.
						</p>
					</div>
					<div class="mt-auto bg-white rounded-lg p-6 shadow-sm border border-gray-100 flex items-center justify-center h-48">
						<div class="flex flex-col items-center gap-3">
							<div class="flex items-center gap-2">
								<div class="h-3 w-3 bg-primary-500 rounded-full animate-pulse"></div>
								<div class="h-3 w-3 bg-primary-400 rounded-full animate-pulse" style="animation-delay: 0.2s"></div>
								<div class="h-3 w-3 bg-primary-300 rounded-full animate-pulse" style="animation-delay: 0.4s"></div>
							</div>
							<span class="text-xs font-medium text-gray-900">AI Learning</span>
						</div>
					</div>
				</div>

				<!-- Card 4: Seamless Integration -->
				<div class="bg-gray-50 rounded-xl p-8 flex flex-col gap-8">
					<h3 class="font-serif text-2xl">Seamless Integration</h3>
					<div class="grid grid-cols-[80px_1fr] gap-8">
						<span class="text-[10px] font-bold uppercase tracking-widest text-gray-400 mt-1">Your Workflow</span>
						<p class="text-sm text-gray-600 leading-relaxed">
							Works via Slack, email, or CRM triggers. Fits into your existing workflow without requiring constant input.
						</p>
					</div>
					<div class="mt-auto bg-white rounded-lg p-6 shadow-sm border border-gray-100 flex items-center justify-center h-48">
						<div class="flex items-center gap-4">
							<div class="flex flex-col items-center gap-2">
								<div class="h-8 w-8 rounded bg-gray-200 flex items-center justify-center text-xs font-bold">📧</div>
								<span class="text-[10px] text-gray-500">Email</span>
							</div>
							<div class="flex flex-col items-center gap-2">
								<div class="h-8 w-8 rounded bg-gray-200 flex items-center justify-center text-xs font-bold">💬</div>
								<span class="text-[10px] text-gray-500">Slack</span>
							</div>
							<div class="flex flex-col items-center gap-2">
								<div class="h-8 w-8 rounded bg-gray-200 flex items-center justify-center text-xs font-bold">⚡</div>
								<span class="text-[10px] text-gray-500">CRM</span>
							</div>
						</div>
					</div>
				</div>
			</div>

			<div class="mt-24 grid grid-cols-[100px_1fr] gap-8 border-t border-gray-200 pt-8">
				<span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-400 mt-3">Get Started</span>
				<div class="flex flex-col gap-8">
					<h3 class="font-serif text-2xl">Ready to speed up your deals?</h3>
					<p class="text-sm text-gray-600 leading-relaxed max-w-lg">
						Join fast-growing companies like Cursor, Clay, and Cartesia. Get contract reviews in hours, not days. Reach out to learn more about how Crosby can accelerate your sales cycle.
					</p>
					<a href="mailto:team@crosby.ai" class="group flex items-center gap-2 text-xs font-bold uppercase tracking-wider text-gray-900">
						CONTACT US
						<div class="flex h-6 w-6 items-center justify-center rounded-full bg-primary-300 text-gray-900 transition-colors group-hover:bg-primary-400">
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
				<span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-900">Customer Stories</span>
				<span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-900">Trusted By Leaders</span>
			</div>

			<h2 class="font-serif text-5xl lg:text-6xl leading-[1.1] text-gray-900 mb-24 max-w-4xl">
				Fast-growing companies rely on Crosby to <span class="underline decoration-1 underline-offset-4 decoration-gray-300">eliminate</span> legal bottlenecks and accelerate their sales cycles.
			</h2>

			<div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
				<div class="relative h-[500px] bg-gray-100 rounded-lg overflow-hidden">
					<img src="/generated/image-professional-male-executive-in-business--1765401801490-2.webp" alt="Jordan, COO at Cursor" class="absolute inset-0 h-full w-full object-cover" />
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
						"Makes contract review a breeze, speeding up our time to revenue. It just works."
					</blockquote>

					<div>
						<p class="text-[10px] font-bold uppercase tracking-widest text-gray-900">Jordan</p>
						<p class="text-[10px] font-bold uppercase tracking-widest text-gray-400 mt-1">COO, Cursor</p>
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
					<h2 class="font-serif text-5xl text-gray-900">Crosby FAQ</h2>
					<p class="text-sm text-gray-600">Got questions? We've got answers.</p>
					<a href="mailto:team@crosby.ai" class="group flex items-center gap-2 text-xs font-bold uppercase tracking-wider text-gray-900 mt-4">
						CONTACT US
						<div class="flex h-6 w-6 items-center justify-center rounded-full bg-primary-300 text-gray-900 transition-colors group-hover:bg-primary-400">
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
											<div class="h-6 w-6 rounded-full bg-primary-300 flex items-center justify-center text-gray-900">
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
				<div class="relative h-[400px] w-full rounded-lg overflow-hidden bg-gray-100">
					<img src="/generated/image-young-professional-working-efficiently-a-1765401803986-3.webp" alt="Efficient work with Crosby" class="absolute inset-0 h-full w-full object-cover" />
				</div>

				<div class="flex flex-col gap-12">
					<div class="flex justify-between items-baseline border-b border-gray-200 pb-4">
						<span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-900">Contract Reviews Solved</span>
					</div>

					<h2 class="font-serif text-5xl lg:text-6xl leading-[1.1] text-gray-900">
						Ready to accelerate your sales cycle?
					</h2>

					<div class="grid grid-cols-[100px_1fr] gap-8 border-t border-gray-200 pt-8">
						<span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-400 mt-3">What Now</span>
						<p class="text-sm leading-relaxed text-gray-600 max-w-sm">
							Join fast-growing companies getting contract reviews in hours, not days. Let's discuss how Crosby can help your team close deals faster.
						</p>
					</div>

					<div class="grid grid-cols-[100px_1fr] gap-8 border-t border-gray-200 pt-8">
						<span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-400 mt-3">Start Today</span>
						<a href="mailto:team@crosby.ai" class="w-fit group flex items-center gap-2 rounded-full bg-black pl-6 pr-1 py-1 text-xs font-bold uppercase tracking-wider text-white transition-colors hover:bg-gray-800">
							GET IN TOUCH
							<div class="flex h-8 w-8 items-center justify-center rounded-full bg-primary-300 text-gray-900 transition-colors group-hover:bg-primary-400">
								<svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
							</div>
						</a>
					</div>
				</div>
			</div>
		</div>
	</section>
</div>

