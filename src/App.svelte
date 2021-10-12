<script>
import Card from "./Card.svelte"
</script>

<main>
<Card>
	<div>
		<h3>Card</h3>
		<p>This is our card</p>
	</div>
	<button slot="button">Test button</button>
</Card>
</main>

<style>
	main {
		display: flex;
		flex-direction: column;
		align-items: center;
	}
</style>