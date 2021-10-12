<script>
	let name;
	let num;
	let isChecked = true;
	let value = 2;
	let selected;

	let questions = [
		{id: 1, text: "What is your fav color?"},
		{id: 2, text: "What is your fav fruit?"},
	]
</script>

<main>
<input type="text" bind:value={name}>
<input type="number" bind:value={num}>
<input type="checkbox" bind:checked={isChecked}>
<input type="radio" bind:group={value} value={1}>
<input type="radio" bind:group={value} value={2}>
<input type="radio" bind:group={value} value={3}>

<select bind:value={selected}>
{#each questions as question}
<option value={question}>
{question.text}
</option>
{/each}
</select>

</main>

<style>
	main {
		display: flex;
		flex-direction: column;
		align-items: center;
	}
</style>