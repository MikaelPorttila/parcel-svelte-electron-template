<script>
	import Hello from './Hello.svelte';
</script>

<section>
	<h1>Parcel + Electron + Svelte Template</h1>
	<Hello/>
</section>

<style>

	@font-face {
		font-family: "FiraCodeCdnFallback";
		src: url(https://cdn.jsdelivr.net/gh/tonsky/FiraCode@1.206/distr/fira_code.css);
	}

	:global(body){
		margin: 10px;
		padding: 0;
		background-color: #eee;
		font-family: "Fira Code", monospace, FiraCodeCdnFallback !important;
		font-feature-settings: "calt" 1;
		font-variant-ligatures: contextual;
		font-weight: 500;
	}

	h1{
		text-align: center;
	}
</style>