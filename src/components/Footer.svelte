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
		<a href="https://github.com/whispr-app/" target="_blank">GitHub</a>
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
		padding: 10px;
		height: 12rem;
		display: flex;
		justify-content: space-evenly;
		align-items: center;

		div > * {
			text-align: center;
			display: block;
		}
	}

	@media screen and (max-width: 830px) {
		footer {
			flex-direction: column;
			height: auto;
		}
	}
</style>
