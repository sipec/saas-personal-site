<script lang="ts">
	import BottomMenu from '$lib/BottomMenu.svelte'
</script>

<div class="bg">
	<div class="col">
		<slot />
		<BottomMenu />
	</div>
</div>

<style>
	.bg {
		background-color: #8d0aff;
		background-image: linear-gradient(#8e0aff, #fb0eb0);
		height: 100vh;
		width: 100vw;
		overflow: auto;
		position: absolute;
		color: #ffeffb;
		font-family: 'Rubik', sans-serif;
	}
	.col {
		max-width: 400px;
		min-height: 100%;
		margin: auto;
		display: flex;
		flex-direction: column;
		align-items: center;
		/* gap: 2rem; */
		padding: 3rem 0;
	}
</style>
