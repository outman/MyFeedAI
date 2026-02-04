<script>
	import logo from '$lib/assets/logo.png';
</script>

<svelte:head>
	<title>Privacy Policy - MyFeedAI</title>
	<meta
		name="description"
		content="MyFeedAI Privacy Policy - Learn how we protect your privacy with our local-first, no-data-collection approach."
	/>
</svelte:head>

<div class="min-h-screen bg-gradient-to-br from-slate-900 via-slate-800 to-slate-900">
	<!-- Header -->
	<header class="container mx-auto px-4 py-12 text-center">
		<div class="mb-6 flex justify-center">
			<img src={logo} alt="MyFeedAI Logo" class="h-16 w-auto" />
		</div>
		<h1 class="mb-4 text-4xl font-bold text-white sm:text-5xl">Privacy Policy</h1>
		<p class="mx-auto max-w-2xl text-lg text-slate-300">
			Your privacy is our priority. MyFeedAI is built with a privacy-first approach, ensuring your data stays on your device.
		</p>
		<div class="mt-6">
			<a
				href="/"
				class="inline-flex items-center gap-2 text-cyan-400 transition-colors hover:text-cyan-300"
			>
				<svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
					<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 19l-7-7m0 0l7-7m-7 7h18" />
				</svg>
				Back to Home
			</a>
		</div>
	</header>

	<!-- Privacy Content -->
	<main class="container mx-auto px-4 pb-16">
		<div class="mx-auto max-w-3xl space-y-8">
			<!-- Last Updated -->
			<div class="rounded-lg border border-slate-700 bg-slate-800/30 p-4 text-center text-slate-400">
				<p>Last Updated: 2026-02-04</p>
			</div>

			<!-- Section 1: No Data Collection -->
			<section
				class="rounded-xl border border-slate-700 bg-slate-800/50 p-8 backdrop-blur-sm"
			>
				<div class="mb-6 flex items-center gap-4">
					<div class="flex h-12 w-12 items-center justify-center rounded-lg bg-red-500/20">
						<svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-red-400" fill="none" viewBox="0 0 24 24" stroke="currentColor">
							<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M18.364 18.364A9 9 0 005.636 5.636m12.728 12.728A9 9 0 015.636 5.636m12.728 12.728L5.636 5.636" />
						</svg>
					</div>
					<h2 class="text-2xl font-bold text-white">No Data Collection</h2>
				</div>
				<div class="space-y-4 text-slate-300">
					<p>
						MyFeedAI is designed as a <strong class="text-white">local-first application</strong>. We do not collect,
						store, or transmit any personal data to external servers. All your feeds, articles, preferences, and AI
						configurations are stored exclusively on your device.
					</p>
					<ul class="ml-6 list-disc space-y-2 text-slate-400">
						<li>No user accounts or authentication required</li>
						<li>No usage analytics or tracking</li>
						<li>No cookies or tracking pixels</li>
						<li>No telemetry data sent to any server</li>
					</ul>
				</div>
			</section>

			<!-- Section 2: No Data Sharing -->
			<section
				class="rounded-xl border border-slate-700 bg-slate-800/50 p-8 backdrop-blur-sm"
			>
				<div class="mb-6 flex items-center gap-4">
					<div class="flex h-12 w-12 items-center justify-center rounded-lg bg-green-500/20">
						<svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-green-400" fill="none" viewBox="0 0 24 24" stroke="currentColor">
							<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z" />
						</svg>
					</div>
					<h2 class="text-2xl font-bold text-white">No Data Sharing</h2>
				</div>
				<div class="space-y-4 text-slate-300">
					<p>
						Since we don't collect any data, we have nothing to share. We <strong class="text-white">never sell, rent,
						or share</strong> your information with third parties. Your reading habits, subscriptions, and AI interactions
						remain completely private.
					</p>
					<div class="mt-4 rounded-lg border border-slate-600 bg-slate-700/30 p-4">
						<p class="text-sm text-slate-400">
							<strong class="text-cyan-400">Note:</strong> When using AI features, the content you choose to summarize
							or translate is sent to the AI provider you configure. This is entirely under your control, and we
							have no visibility into these requests.
						</p>
					</div>
				</div>
			</section>

			<!-- Section 3: Legal Compliance -->
			<section
				class="rounded-xl border border-slate-700 bg-slate-800/50 p-8 backdrop-blur-sm"
			>
				<div class="mb-6 flex items-center gap-4">
					<div class="flex h-12 w-12 items-center justify-center rounded-lg bg-blue-500/20">
						<svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-blue-400" fill="none" viewBox="0 0 24 24" stroke="currentColor">
							<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 6l3 1m0 0l-3 9a5.002 5.002 0 006.001 0M6 7l3 9M6 7l6-2m6 2l3-1m-3 1l-3 9a5.002 5.002 0 006.001 0M18 7l3 9m-3-9l-6-2m0-2v2m0 16V5m0 16H9m3 0h3" />
						</svg>
					</div>
					<h2 class="text-2xl font-bold text-white">Legal Compliance</h2>
				</div>
				<div class="space-y-4 text-slate-300">
					<p>
						MyFeedAI's privacy-first design naturally aligns with global data protection regulations. Since we don't
						collect or process personal data:
					</p>
					<ul class="ml-6 list-disc space-y-2 text-slate-400">
						<li><strong class="text-white">GDPR:</strong> No personal data processing means GDPR does not apply to our application</li>
						<li><strong class="text-white">CCPA:</strong> No data collection means no data to delete or share</li>
						<li><strong class="text-white">COPPA:</strong> Safe for users of all ages as no data is collected</li>
					</ul>
					<p class="mt-4">
						We believe privacy is a fundamental right. Our commitment to zero data collection goes beyond minimum
						legal requirements—it's the core of our product philosophy.
					</p>
				</div>
			</section>

			<!-- Section 4: Contact Information -->
			<section
				class="rounded-xl border border-slate-700 bg-slate-800/50 p-8 backdrop-blur-sm"
			>
				<div class="mb-6 flex items-center gap-4">
					<div class="flex h-12 w-12 items-center justify-center rounded-lg bg-purple-500/20">
						<svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-purple-400" fill="none" viewBox="0 0 24 24" stroke="currentColor">
							<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
						</svg>
					</div>
					<h2 class="text-2xl font-bold text-white">Contact Information</h2>
				</div>
				<div class="space-y-4 text-slate-300">
					<p>
						If you have any questions, concerns, or suggestions about our privacy practices, please don't hesitate to
						reach out to us. We value your feedback and are committed to maintaining your trust.
					</p>
					<div class="mt-6 flex flex-col items-center gap-4 sm:flex-row">
						<a
							href="mailto:pochonlee@gmail.com"
							class="inline-flex w-full items-center justify-center gap-2 rounded-lg bg-cyan-500 px-6 py-3 font-semibold text-white transition-colors hover:bg-cyan-600 sm:w-auto"
						>
							<svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
								<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
							</svg>
							pochonlee@gmail.com
						</a>
					</div>
				</div>
			</section>

			<!-- Commitment Statement -->
			<section
				class="rounded-xl border border-cyan-500/30 bg-cyan-500/5 p-8 text-center backdrop-blur-sm"
			>
				<svg xmlns="http://www.w3.org/2000/svg" class="mx-auto mb-4 h-16 w-16 text-cyan-400" fill="none" viewBox="0 0 24 24" stroke="currentColor">
					<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z" />
				</svg>
				<h3 class="mb-2 text-xl font-bold text-white">Our Privacy Promise</h3>
				<p class="text-slate-300">
					We are committed to keeping MyFeedAI truly private. No hidden tracking, no data collection—just a powerful
					RSS reader that respects your digital sovereignty.
				</p>
			</section>
		</div>
	</main>

	<!-- Footer -->
	<footer class="border-t border-slate-800 py-8 text-center text-slate-500">
		<p>&copy; 2026 scrapmind.com All rights reserved.</p>
	</footer>
</div>
