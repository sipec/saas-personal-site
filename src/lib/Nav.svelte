<script lang="ts">
	import Logo from '$lib/Logo.svelte'
	import { HeartIcon } from 'svelte-feather-icons'
</script>

<div class="top">
	<img src="/me.jpg" alt="" />
	<div>
		<Logo />
		<div class="row">
			<a href="/work">work</a>
			<a
				href="https://sinclaaair.notion.site/Date-Me-487ef432c1f54938bf5e7a45ef05d57b"
				target="_blank"
			>
				<HeartIcon />play
			</a>
		</div>
	</div>
</div>

<style>
	img {
		height: 96px;
		width: 96px;
		border-radius: 100%;
	}

	.top {
		display: flex;
		gap: 1rem;
	}

	.row {
		display: flex;
		justify-content: space-between;
	}

	a:hover {
		color: #ffbae8;
	}

	a > :global(svg) {
		height: 12px;
		stroke-width: 4px;
		display: inline;
	}
</style>
