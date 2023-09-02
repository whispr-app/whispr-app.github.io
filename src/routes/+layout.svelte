<slot />

<style lang="scss">
	@use '../styles/colours.scss' as colours;

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
