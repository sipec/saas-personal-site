<script lang="ts">
	import Logo from './logo.svelte'
</script>

<nav>
	<Logo />
	<span class="menu-items">
		<a href="https://manifold.markets/Sinclair">Bets</a>
		<a href="https://www.admonymous.co/si">Feedback</a>
		<a href="/work">Features</a>
		<a href="/contact">Contact Me</a>
	</span>
</nav>

<style>
	nav {
		display: flex;
		align-items: center;
		margin: 16px;
	}
	.menu-items {
		display: flex;
		flex-wrap: wrap;
		gap: 16px;
		margin-left: 40px;
	}

	a {
		text-decoration: none;
		font-size: 20px;
	}
</style>
