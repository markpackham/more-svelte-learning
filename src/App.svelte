<script>
import Card from "./Card.svelte"
</script>

<main>
<Card>
	<p>This is our card</p>
	<button>Test button</button>
</Card>
</main>

<style>
	main {
		display: flex;
		flex-direction: column;
		align-items: center;
	}
</style>