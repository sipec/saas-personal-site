<script lang="ts">
	export let href: string
	export let label: string
</script>

<a {href} target="_blank">
	<slot />
	{label}
	<div />
</a>

<style>
	a {
		padding: 1rem 0.5rem;
		width: 100%;
		display: flex;
		justify-content: space-between;
		color: white;
	}
	a:hover,
	a:focus-visible {
		color: yellow;
		background-color: rgba(256, 256, 256, 0.1);
	}
</style>
