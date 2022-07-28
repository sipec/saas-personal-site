<script lang="ts">
	import TopMenu from '$lib/TopMenu.svelte'
</script>

<div class="main">
	<TopMenu />
	<slot />
</div>

<style>
	.main {
		background-color: #8d0aff;
		height: 100vh;
		width: 100vw;
		position: absolute;
		color: white;
		font-family: 'Rubik', sans-serif;
	}
</style>
