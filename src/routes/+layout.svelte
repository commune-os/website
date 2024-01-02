<script>
	import Footer from '$lib/components/Footer.svelte';
	import Header from '$lib/components/header.svelte';
	import '../app.css';
</script>

<svelte:head>
    <title>Commune</title>
</svelte:head>

<Header />
<slot />
<Footer />
