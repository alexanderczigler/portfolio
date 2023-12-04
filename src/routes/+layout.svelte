<script>
	import './app.css';
</script>

<div class="app">
	<h1>Alexander Czigler</h1>
	<hr class="narrow-hr" />

	<main>
		<slot />
	</main>

	<hr class="narrow-hr" />
	<footer>
		<p>Contact: firstname at lastname dot eu</p>
	</footer>
</div>

<style>
	footer p {
		color: #a0a0a0;
	}
</style>
