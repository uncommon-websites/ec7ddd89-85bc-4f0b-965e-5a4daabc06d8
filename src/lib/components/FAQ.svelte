<script>
	let openIndex = 0;
	const faqs = [
		{
			question: "What types of assets can be used as collateral?",
			answer: "We accept unlisted shares in startups, partnership stakes, fund commitments, and other illiquid ownership positions. Our AI-powered analysis can evaluate complex structures that traditional banks typically reject."
		},
		{
			question: "How discreet is the process?",
			answer: "Completely confidential. Your loan won't affect your company or make your ownership stake visible to others. We understand that privacy is paramount for high-net-worth individuals and founders."
		},
		{
			question: "How long does it take to get funding?",
			answer: "We provide a concrete loan proposal within a few days of your initial consultation. Once approved, funds are typically disbursed within 3-5 business days."
		},
		{
			question: "Do I need to sell my shares?",
			answer: "No. That's the entire point. Fuels provides liquidity through collateralized lending, allowing you to access capital while maintaining your ownership stake and future upside potential."
		},
		{
			question: "What are the typical loan terms?",
			answer: "Terms vary based on your specific situation and collateral. We offer flexible structures with competitive rates, typically ranging from 12-36 months. Everything is customized to your needs."
		},
		{
			question: "Is Fuels regulated?",
			answer: "Yes. Fuels operates under 0TO9 AB, a licensed credit market company authorized to conduct financing operations under Swedish law (2004:297) regarding banking and financing operations."
		}
	];
</script>

<section class="py-24">
	<div class="mx-auto max-w-[1400px] px-6">
		<div class="grid grid-cols-1 gap-16 lg:grid-cols-12">
			<!-- Left Side -->
			<div class="lg:col-span-4">
				<div class="mb-4 text-[10px] font-bold tracking-widest text-gray-500 uppercase">[05] FAQ</div>
				<h2 class="mb-6 text-4xl font-medium tracking-tight text-gray-900">Your questions, answered</h2>
				<p class="mb-8 text-lg leading-relaxed text-gray-600">
					Have more questions? Our team is ready to discuss your specific situation in a confidential consultation.
				</p>
				<a href="mailto:hello@fuelscapital.com" class="inline-block bg-gray-900 px-6 py-3 text-[11px] font-bold tracking-widest text-white transition-colors hover:bg-gray-800 uppercase">
					Contact Us
				</a>
			</div>

			<!-- Right Side (Accordion) -->
			<div class="lg:col-span-8">
				<div class="divide-y divide-gray-200 border-t border-b border-gray-200">
					{#each faqs as faq, i}
						<div class="group">
							<button 
								class="flex w-full items-center justify-between py-6 text-left focus:outline-none"
								onclick={() => openIndex = openIndex === i ? -1 : i}
							>
								<span class="text-lg font-medium text-gray-900">{faq.question}</span>
								<span class="ml-4 flex h-6 w-6 items-center justify-center text-gray-400">
									{#if openIndex === i}
										<svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M18 6L6 18M6 6l12 12"/></svg>
									{:else}
										<svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 5v14M5 12h14"/></svg>
									{/if}
								</span>
							</button>
							{#if openIndex === i}
								<div class="pb-6 text-gray-600 leading-relaxed">
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