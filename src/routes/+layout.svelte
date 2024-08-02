<div class="mainContainer">
	<slot />
</div>

<style>
	.mainContainer {
		min-height: 100vh;
		background: linear-gradient(to right, #000428, #00004b, #050f64);
		color: white;
		position: relative;
		display: flex;
		flex-direction: column;
	}
</style>
