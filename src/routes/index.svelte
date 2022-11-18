<script>
	import IconLink from '$lib/IconLink.svelte'
	import Link from '$lib/Link.svelte'
	import Nav from '$lib/Nav.svelte'
	import {
		GithubIcon,
		TwitterIcon,
		TwitchIcon,
		CalendarIcon,
		MessageCircleIcon,
		InstagramIcon,
		LinkedinIcon,
		TvIcon,
	} from 'svelte-feather-icons'
</script>

<div class="section">
	<Nav />
	<main>
		<Link href="https://manifold.markets/Sinclair" label="manifold"><span /></Link>
		<Link href="https://github.com/sipec" label="github"><GithubIcon /></Link>
		<Link href="https://twitter.com/SinclarityChen" label="twitter"><TwitterIcon /></Link>
		<Link href="https://discord.com/users/257305864988393483" label="discord"><TwitchIcon /></Link>
		<Link href="https://usemotion.com/meet/sinclair-chen/hii" label="book me">
			<CalendarIcon />
		</Link>
		<Link href="https://admonymous.co/si" label="message"><MessageCircleIcon /></Link>
	</main>
	<div class="other">
		<IconLink href="https://www.instagram.com/clairitable/"><InstagramIcon /></IconLink>
		<IconLink href="https://www.linkedin.com/in/clarity-chen/"><LinkedinIcon /></IconLink>
		<IconLink href="https://anilist.co/user/sinclaether/"><TvIcon /></IconLink>
	</div>
</div>

<style>
	main {
		align-self: stretch;
		margin-top: 2rem;
		display: flex;
		flex-direction: column;
		border-top: 2px solid #3cacf6;
	}
	main > :global(*) {
		border-bottom: 2px solid #3cacf6;
	}

	.other {
		margin-top: 2rem;
		display: flex;
		justify-content: space-around;
	}
</style>
