<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>
<div class="flex min-h-screen w-full flex-col text-white bg-[#002234] overflow-x-hidden" style="font-family: 'Poppins'">
	<header class="flex w-full justify-between items-center bg-[#002234]">
		<img src="/vechain-logo.svg" alt="Vechain logo" class="w-[35%] pl-5 pt-5" />
		<div class="pr-5 pt-5 text-white font-semibold">EN</div>
	</header>
	<main class="flex-1 bg-[#002234]">{@render children()}</main>
	<footer class="h-[260px] w-full items-center justify-between bg-black flex flex-col">
		<img src="/ATP-x-VeChain-2.svg" alt="Vechain X ATP" class="h-[69px] w-full max-w-[390px] px-4 mt-8" />
		<div class="text-white text-center mb-8">
			<a href="/" class = "hover:underline"><b>PRIVACY POLICY</b></a>
			<span>-</span>
			<a href="/" class = "hover:underline"><b>CONTACT US</b></a><br>
			Provided By Vechain
		</div>
	</footer>
</div>
