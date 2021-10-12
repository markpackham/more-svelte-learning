<script>
	import Button from "./Button.svelte"
</script>

<main>
	<Button btnText="Overriden"/>
</main>

<style>
	h5, p {
		margin: 4px 0px;
	}
	.card {
		min-width: 400px;
		padding: 8px;
		border-radius: 20px;
		border: 2px solid gray;
		margin-top: 8px;
	}
	main {
		display: flex;
		flex-direction: column;
		align-items: center;
	}
	h1 {
		font-size: 72px;
		text-align: center;
	}
	h3 {
		font-size: 38px;
	}
</style>