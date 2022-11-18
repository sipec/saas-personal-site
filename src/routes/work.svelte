<script>
	import Nav from '$lib/Nav.svelte'
</script>

<div>
	<Nav page="work" />
	<main>
		<h1>projects</h1>
		🚧 page is wip in progress 🚧
		<br /><br />
		<a href="https://oneword.games">One Word</a>
		<a href="https://tilt-to-tilt.netlify.app">Tilt to Live</a>
		<a href="https://sipec.github.io/project.html">Taste the Waste</a>
		<br />
		<a href="https://sinclaaair.notion.site/Sinclair-s-Resume-1f1c0c3e2a234655881de9d263586411">
			Resume
		</a>
	</main>
</div>

<style>
	main {
		margin-top: 4rem;
	}

	h1 {
		font-size: 36px;
	}

	a {
		color: aqua;
		display: block;
	}
	a:hover {
		text-decoration: underline;
	}
</style>
