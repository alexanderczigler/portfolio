<script>
	import GitHub from '../iconoir/GitHub.svelte';
	import Suitcase from '../iconoir/Suitcase.svelte';
	import LinkedIn from '../iconoir/LinkedIn.svelte';
</script>

<svelte:head>
	<title>Alexander Czigler</title>
</svelte:head>

<h1>Alexander Czigler</h1>

<span>
	<a href="https://iteam.se" target="_blank" rel="noreferrer">
		<Suitcase />
	</a>

	<a href="https://github.com/alexanderczigler" target="_blank" rel="noreferrer">
		<GitHub />
	</a>

	<a href="https://www.linkedin.com/in/alexanderczigler" target="_blank" rel="noreferrer">
		<LinkedIn />
	</a>
</span>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Fira+Code:wght@300');

	a,
	a:hover,
	a:visited {
		color: #000000;
		text-decoration: none;
	}

	h1 {
		color: #252323;
		font-family: 'Fira Code';
		font-weight: 100;
		font-size: 1.5rem;
	}
</style>
