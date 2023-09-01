<slot />

<style lang="scss">
	@use '../styles/colours.scss' as colours;

	@font-face {
		font-family: 'Mona Sans';
		src: url('Mona-Sans.woff2') format('woff2 supports variations'),
			url('Mona-Sans.woff2') format('woff2-variations');
		font-weight: 200 900;
		font-stretch: 75% 125%;
	}

	:global(html) {
		font-family: 'Mona Sans';
		padding: 0;
		margin: 0;
	}

	:global(body) {
		padding: 0;
		margin: 0;
		width: 100%;
		height: 100%;
		background-color: colours.$background-100;
		color: colours.$text-100;
	}

	:global(a) {
		color: colours.$primary-100;
	}
</style>
