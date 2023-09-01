<script lang="ts">
	import WhisprLogoWhite from './whispr-logo-white.svelte';
	import Button from './Button.svelte';
</script>

<header>
	<a href="/" class="logo">
		<WhisprLogoWhite />
	</a>
	<div class="options">
		<Button>Download</Button>
	</div>
</header>

<style lang="scss">
	@use '../styles/colours.scss' as colours;

	.logo {
		width: 10rem;
		display: flex;
		justify-content: center;
		align-items: center;
	}

	.options {
		display: flex;
		justify-content: center;
		align-items: center;
		gap: 1rem;
	}

	header {
		display: flex;
		justify-content: space-between;
		align-items: center;
		padding: 0.5rem 1rem;
		box-sizing: border-box;
		height: 4rem;
		width: 100%;
		margin: 0;
		background-color: colours.$background-secondary-50;
		color: colours.$text-100;
		position: sticky;
		backdrop-filter: blur(10px);
		top: 0;
	}
</style>
