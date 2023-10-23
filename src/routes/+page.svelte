<script>
	import GitHub from '../iconoir/GitHub.svelte';
	import LinkedIn from '../iconoir/LinkedIn.svelte';
	import Pages from '../iconoir/Pages.svelte';
</script>

<svelte:head>
	<title>Alexander Czigler</title>
</svelte:head>

<h1>Alexander Czigler</h1>

<span>
	<a href="https://ilix.se/alexanderczigler-cv.pdf" target="_blank" rel="noreferrer">
		<Pages />
	</a>

	<a href="https://github.com/alexanderczigler" target="_blank" rel="noreferrer">
		<GitHub />
	</a>

	<a href="https://www.linkedin.com/in/ilix" target="_blank" rel="noreferrer">
		<LinkedIn />
	</a>
</span>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Fira+Code:wght@300');

	a,
	a:visited {
		color: #0b4371;
		text-decoration: none;
	}

	a:hover {
		color: #70390b;
	}

	h1 {
		color: #0b4371;
		font-family: 'Fira Code';
		font-weight: 100;
		font-size: 1.5rem;
	}
</style>
