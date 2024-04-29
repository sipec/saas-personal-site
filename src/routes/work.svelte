<script>
	import Nav from '$lib/Nav.svelte'
</script>

<div>
	<Nav />
	<main>
		<div>not looking at the moment!</div>
		<br />
		<a href="https://sinclaaair.notion.site/Sinclair-s-Resume-1f1c0c3e2a234655881de9d263586411">
			Resume
		</a>
		<br /> <br />
		<h1>past projects</h1>
		<br />
		<a href="https://oneword.games">One Word</a>
		<a href="https://tilt-to-tilt.netlify.app">Tilt to Live</a>
		<a href="https://sipec.github.io/project.html">Taste the Waste</a>
		<br />
	</main>
</div>

<style>
	main {
		margin-top: 4rem;
	}

	h1 {
		margin: 0;
	}

	a {
		color: aqua;
		display: block;
	}
	a:hover {
		text-decoration: underline;
	}
</style>
