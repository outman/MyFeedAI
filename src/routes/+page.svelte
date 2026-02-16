<script>
	import logo from '$lib/assets/logo.png';
	import screenshot1 from '$lib/assets/1280_1@1x.png';
	import screenshot2 from '$lib/assets/1280_2@1x.png';
	import screenshot3 from '$lib/assets/1280_3@1x.png';
	import screenshot4 from '$lib/assets/1280_4@1x.png';
	import { base } from '$app/paths';
</script>

<svelte:head>
	<title>MyFeedAI - Privacy-First RSS Reader with AI</title>
	<meta
		name="description"
		content="A privacy-focused RSS reader featuring local storage, custom AI integration for summaries and translation, and flexible data import options."
	/>
</svelte:head>

<div class="min-h-screen bg-gradient-to-br from-slate-900 via-slate-800 to-slate-900">
	<!-- Header / Hero Section -->
	<header class="container mx-auto px-4 py-16 text-center">
		<div class="mb-8 flex justify-center">
			<img src={logo} alt="MyFeedAI Logo" class="h-24 w-auto" />
		</div>
		<h1 class="mb-4 bg-gradient-to-r from-cyan-400 to-blue-500 bg-clip-text text-5xl font-bold text-transparent sm:text-6xl">
			MyFeedAI
		</h1>
		<p
			class="mx-auto max-w-2xl text-lg text-slate-300 sm:text-xl"
		>
			A privacy-focused RSS reader featuring local storage, custom AI integration for summaries and translation,
			and flexible data import options.
		</p>
		<div class="mt-8 flex justify-center">
			<a
				href="https://apps.apple.com/us/app/myfeed-ai/id6758687177?mt=12"
				target="_blank"
				rel="noopener noreferrer"
				class="inline-flex items-center gap-3 rounded-xl bg-black px-6 py-3 font-semibold text-white transition-all hover:scale-105 hover:bg-gray-900"
			>
				<svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8" viewBox="0 0 24 24" fill="currentColor">
					<path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.81-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/>
				</svg>
				<div class="flex flex-col text-left">
					<span class="text-xs">Download on the</span>
					<span class="text-lg leading-tight">Mac App Store</span>
				</div>
			</a>
		</div>
	</header>

	<!-- Features Section -->
	<section class="container mx-auto px-4 py-16">
		<h2 class="mb-12 text-center text-3xl font-bold text-white">Features</h2>
		<div class="grid gap-8 md:grid-cols-2 lg:grid-cols-2">
			<!-- Feature 1 -->
			<div
				class="rounded-xl border border-slate-700 bg-slate-800/50 p-8 backdrop-blur-sm transition-transform hover:scale-[1.02] hover:border-cyan-500/50"
			>
				<div class="mb-4 flex h-12 w-12 items-center justify-center rounded-lg bg-cyan-500/20">
					<svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-cyan-400" fill="none" viewBox="0 0 24 24" stroke="currentColor">
						<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 15v2m-6 4h12a2 2 0 002-2v-6a2 2 0 00-2-2H6a2 2 0 00-2 2v6a2 2 0 002 2zm10-10V7a4 4 0 00-8 0v4h8z" />
					</svg>
				</div>
				<h3 class="mb-2 text-xl font-semibold text-white">Local-First & Privacy-Focused</h3>
				<p class="text-slate-400">
					All data is stored locally on your device to ensure your privacy and security. No data tracking.
				</p>
			</div>

			<!-- Feature 2 -->
			<div
				class="rounded-xl border border-slate-700 bg-slate-800/50 p-8 backdrop-blur-sm transition-transform hover:scale-[1.02] hover:border-cyan-500/50"
			>
				<div class="mb-4 flex h-12 w-12 items-center justify-center rounded-lg bg-cyan-500/20">
					<svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-cyan-400" fill="none" viewBox="0 0 24 24" stroke="currentColor">
						<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z" />
					</svg>
				</div>
				<h3 class="mb-2 text-xl font-semibold text-white">Custom AI Providers</h3>
				<p class="text-slate-400">
					Supports configuration of custom AI providers (BYO-AI), giving you full control over the model you use.
				</p>
			</div>

			<!-- Feature 3 -->
			<div
				class="rounded-xl border border-slate-700 bg-slate-800/50 p-8 backdrop-blur-sm transition-transform hover:scale-[1.02] hover:border-cyan-500/50"
			>
				<div class="mb-4 flex h-12 w-12 items-center justify-center rounded-lg bg-cyan-500/20">
					<svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-cyan-400" fill="none" viewBox="0 0 24 24" stroke="currentColor">
						<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
					</svg>
				</div>
				<h3 class="mb-2 text-xl font-semibold text-white">AI-Powered Insights</h3>
				<p class="text-slate-400">
					Built-in AI capabilities for instant article summarization and seamless translation.
				</p>
			</div>

			<!-- Feature 4 -->
			<div
				class="rounded-xl border border-slate-700 bg-slate-800/50 p-8 backdrop-blur-sm transition-transform hover:scale-[1.02] hover:border-cyan-500/50"
			>
				<div class="mb-4 flex h-12 w-12 items-center justify-center rounded-lg bg-cyan-500/20">
					<svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-cyan-400" fill="none" viewBox="0 0 24 24" stroke="currentColor">
						<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 16v1a3 3 0 003 3h10a3 3 0 003-3v-1m-4-8l-4-4m0 0L8 8m4-4v12" />
					</svg>
				</div>
				<h3 class="mb-2 text-xl font-semibold text-white">Versatile Import Options</h3>
				<p class="text-slate-400">
					Supports multiple methods for importing feed sources, including OPML and more.
				</p>
			</div>
		</div>
	</section>

	<!-- Screenshots Section -->
	<section class="container mx-auto px-4 py-16">
		<h2 class="mb-12 text-center text-3xl font-bold text-white">Screenshots</h2>
		<div class="grid gap-8 md:grid-cols-2">
			<img src={screenshot1} alt="Screenshot 1" class="h-auto w-full shadow-2xl" />
			<img src={screenshot2} alt="Screenshot 2" class="h-auto w-full shadow-2xl" />
			<img src={screenshot3} alt="Screenshot 3" class="h-auto w-full shadow-2xl" />
			<img src={screenshot4} alt="Screenshot 4" class="h-auto w-full shadow-2xl" />
		</div>
	</section>

	<!-- Contact Section -->
	<section class="container mx-auto px-4 py-16">
		<div
			class="mx-auto max-w-2xl rounded-xl border border-slate-700 bg-slate-800/50 p-8 text-center backdrop-blur-sm"
		>
			<h2 class="mb-4 text-2xl font-bold text-white">Get in Touch</h2>
			<p class="text-slate-400">Have questions or feedback? Reach out to us!</p>
			<a
				href="mailto:pochonlee@gmail.com"
				class="mt-6 inline-flex items-center gap-2 rounded-lg bg-cyan-500 px-6 py-3 font-semibold text-white transition-colors hover:bg-cyan-600"
			>
				<svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
					<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
				</svg>
				pochonlee@gmail.com
			</a>
		</div>
	</section>

	<!-- Footer -->
	<footer class="border-t border-slate-800 py-8 text-center text-slate-500">
		<p class="mb-2">&copy; 2026 scrapmind.com All rights reserved.</p>
		<nav class="flex justify-center gap-4">
			<a href="{base}/privacy" class="transition-colors hover:text-slate-300">Privacy Policy</a>
		</nav>
	</footer>
</div>
