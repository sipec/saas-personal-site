<script lang="ts">
	export let href: string
</script>

<a {href}><slot /></a>

<style>
	a {
		color: #3cacf6;
	}
</style>
