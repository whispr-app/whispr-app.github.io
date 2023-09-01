<script lang="ts">
	import WhisprLogoWhite from './whispr-logo-white.svelte';
</script>

<footer>
	<div>
		<a href="/" class="logo">
			<WhisprLogoWhite />
		</a>
		<p>© 2023 Whispr</p>
	</div>
	<div>
		<h3>Product</h3>
		<p>Download</p>
		<p>Open source</p>
	</div>
	<div>
		<h3>Information</h3>
		<p>Acknowledgments</p>
		<p>Licenses</p>
	</div>
</footer>

<style lang="scss">
	@use '../styles/colours.scss' as colours;

	.logo {
		width: 10rem;
		display: flex;
		justify-content: center;
		align-items: center;
	}

	footer {
		height: 12rem;
		display: flex;
		justify-content: space-evenly;
		align-items: center;
	}
</style>
