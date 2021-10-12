<script>
    let show = true;

    const hideAlert = () =>{
        show = false;
    }

let warning = true;
</script>

{#if show}
<div class="alert" class:warning={warning}>
50% off all fruit!
<button on:click={hideAlert}>Hide</button>
</div>
{/if}

<style>
.alert {
	padding: 8px;
	font-size: 18px;
	background-color: darkblue;
	color: white;
}

.warning{
    background-color: darkred;
}
</style>