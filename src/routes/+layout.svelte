<script lang="ts">
	import Header from '$lib/components/Header.svelte';
	import '../app.css';
	import CallToAction from "../lib/components/CallToAction.svelte";
	import Features from "../lib/components/Features.svelte";
	import Footer from "../lib/components/Footer.svelte";
	import Hero from "../lib/components/Hero.svelte";
</script>

<Header />
<Hero/>
<Features/>
<CallToAction/>
<Footer/>
<main>
	<slot />
</main>
