<script>
	const logos = [
		{ name: 'Nordea', width: 100 },
		{ name: 'SEB', width: 100 },
		{ name: 'Handelsbanken', width: 100 },
		{ name: 'Swedbank', width: 80 }
	];
</script>

<section class="relative overflow-hidden border-b border-gray-200 bg-white pt-20 pb-16">
	<!-- Geometric Decoration Top Right -->
	<div class="absolute top-0 right-0 h-64 w-64 opacity-10 pointer-events-none">
		<svg viewBox="0 0 100 100" class="h-full w-full stroke-gray-400" fill="none">
			<path d="M0 0 L100 100 M50 0 L100 50 M0 50 L50 100" stroke-width="0.5" />
			<rect x="50" y="0" width="50" height="50" stroke-width="0.5" />
		</svg>
	</div>

	<div class="mx-auto max-w-[1400px] px-6">
		<div class="max-w-3xl">
			<!-- Badge -->
			<a href="#" class="mb-8 inline-flex items-center gap-2 rounded-full border border-gray-200 bg-gray-50 px-3 py-1 text-[10px] font-bold tracking-widest text-gray-700 hover:bg-gray-100 uppercase">
				<span class="text-gray-500">Licensed</span>
				Swedish Credit Market Company &rsaquo;
			</a>

			<!-- Headline -->
			<h1 class="mb-6 text-7xl font-medium tracking-tight text-gray-900">
				Paper rich,<br>cash poor?
			</h1>

			<!-- Subhead -->
			<p class="mb-10 max-w-xl text-lg leading-relaxed text-gray-600">
				Fuels converts <strong class="font-semibold text-gray-900">illiquid assets into immediate capital</strong> through collateralized lending. Access the liquidity you need without selling your ownership stake.
			</p>

			<!-- Buttons -->
			<div class="mb-24 flex items-center gap-4">
				<a href="#" class="bg-gray-900 px-6 py-3 text-[11px] font-bold tracking-widest text-white transition-colors hover:bg-gray-800 uppercase">
					Schedule Meeting
				</a>
				<a href="#" class="border border-gray-200 bg-white px-6 py-3 text-[11px] font-bold tracking-widest text-gray-900 transition-colors hover:bg-gray-50 uppercase">
					How It Works
				</a>
			</div>
		</div>

		<!-- Trust Indicators -->
		<div class="flex flex-wrap items-center gap-12 border-t border-gray-200 pt-8">
			<div class="flex items-center gap-3">
				<div class="flex h-10 w-10 items-center justify-center rounded-full bg-gray-900 text-white font-bold text-xs">
					<svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg>
				</div>
				<div>
					<div class="text-xs font-bold text-gray-900 uppercase tracking-widest">Licensed</div>
					<div class="text-xs text-gray-500">Credit Market Company</div>
				</div>
			</div>
			<div class="flex items-center gap-3">
				<div class="flex h-10 w-10 items-center justify-center rounded-full bg-gray-900 text-white font-bold text-xs">
					<svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 2v20M2 12h20"/></svg>
				</div>
				<div>
					<div class="text-xs font-bold text-gray-900 uppercase tracking-widest">Discreet</div>
					<div class="text-xs text-gray-500">Confidential Process</div>
				</div>
			</div>
			<div class="flex items-center gap-3">
				<div class="flex h-10 w-10 items-center justify-center rounded-full bg-gray-900 text-white font-bold text-xs">
					<svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M13 2L3 14h9l-1 8 10-12h-9l1-8z"/></svg>
				</div>
				<div>
					<div class="text-xs font-bold text-gray-900 uppercase tracking-widest">Fast</div>
					<div class="text-xs text-gray-500">Decision in Days</div>
				</div>
			</div>
		</div>
	</div>
</section>