<script>
	import GitHub from '../iconoir/GitHub.svelte';
	import LinkedIn from '../iconoir/LinkedIn.svelte';
	import Pages from '../iconoir/Pages.svelte';
</script>

<svelte:head>
	<title>Alexander Czigler</title>
</svelte:head>

<h1>Alexander Czigler</h1>
<hr />

<p>Links</p>

<div class="list">
	<ul>
		<li>
			<a href="https://ilix.se/alexanderczigler-cv.pdf" target="_blank" rel="noreferrer">
				<Pages /> CV
			</a>
		</li>
		<li>
			<a href="https://github.com/alexanderczigler" target="_blank" rel="noreferrer">
				<GitHub /> GitHub
			</a>
		</li>
		<li>
			<a href="https://www.linkedin.com/in/alexanderczigler" target="_blank" rel="noreferrer">
				<LinkedIn /> LinkedIn
			</a>
		</li>
	</ul>
</div>

<hr />

<p>&copy;2023 Alexander Czigler</p>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Fira+Code:wght@300');

	body {
		font-family: 'Fira Code', monospace;
		background-color: #fff;
		color: #000;
	}

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
		font-weight: 100;
		font-size: 1.5rem;
	}

	.list ul {
		list-style: none;
		padding: 0;
	}

	.list li {
		margin-bottom: 0.5rem;
	}

	hr {
		border: 0;
		height: 1px;
		background-color: #ccc;
	}
</style>
