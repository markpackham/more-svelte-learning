<script>
	let src = "favicon.png";

	let firstName = "";
	let lastName = "";

	$: fullname = `${firstName} ${lastName}`;
	$: {
		console.log(firstName)
		console.log(lastName)
	}

</script>

<main>
	<h1>Hello {fullname}</h1>

	<input type="text" bind:value={firstName}>
	<input type="text" bind:value={lastName}>

	<img {src} alt="Svelte logo">
</main>

<style>
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