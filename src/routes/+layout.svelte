<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>
<div class="flex min-h-screen flex-col text-white bg-[#002234]" style="font-family: 'Poppins'">
	<header class="px-6, flex h-[58px] w-full items-center justify-between bg-[#002234] p-6">
		<img src="/vechain-logo.svg" alt="Vechain logo" class="h-6 w-[131px]" />
		<div class="mr-4 text-white">EN</div>
	</header>
	<main class="flex-1 bg-[#002234]">{@render children()}</main>
	<footer class="h-[260px] w-full items-center justify-between bg-black flex flex-col">
		<img src="/ATP-x-VeChain-2.svg" alt="Vechain X ATP" class="h-[69px] w-[390px] mt-8" />
		<div class="text-white text-center mb-8">
			<a href="/" class = "hover:underline"><b>PRIVACY POLICY</b></a>
			<span>-</span>
			<a href="/" class = "hover:underline"><b>CONTACT US</b></a><br>
			Provided By Vechain
		</div>
	</footer>
</div>
