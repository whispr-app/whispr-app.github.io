<div class="button">
	<slot />
</div>

<style lang="scss">
	@use '../styles/colours.scss' as colours;

	.button {
		display: flex;
		justify-content: center;
		align-items: center;
		padding: 0.5rem;

		background-color: colours.$button-100;
		color: colours.$text-100;
		border-radius: 15px;
		border: 1px solid colours.$outline-100;

		transition: border 0.2s ease-in-out;

		&:hover {
			border: 1px solid colours.$outline-highlighted-100;
			cursor: pointer;
		}
	}
</style>
