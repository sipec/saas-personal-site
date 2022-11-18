<script lang="ts">
	export let href: string
</script>

<a {href} target="_blank">
	<slot />
</a>

<style>
	a {
		padding: 0.25rem;
		border-radius: 0.25rem;
	}
	a:focus {
		color: yellow;
	}
</style>
