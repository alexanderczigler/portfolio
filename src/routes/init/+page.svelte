<svelte:head>
	<title>Alexander Czigler</title>
</svelte:head>

<h2>init</h2>
<p>
	This is mostly for my own use. I use this to quickly set up a new machine with my zsh profile.
</p>
<pre>
  curl https://raw.githubusercontent.com/alexanderczigler/dotfiles/main/.zshrc > ~/.zshrc.custom
  echo ". ~/.zshrc.custom" >> ~/.zshrc
  source ~/.zshrc
</pre>

<style>
	pre {
		background-color: #040404;
		color: #abb2bf;
		font-family: 'Fira Code', 'Consolas', 'Courier New', monospace;
		font-size: 0.7em;
		padding: 1rem;
		border-radius: 5px;
		overflow-x: auto;
		width: 100%;
		max-width: 600px;
		line-height: 1.5;
	}
</style>
