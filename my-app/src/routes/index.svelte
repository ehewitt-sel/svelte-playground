<script>
	let name = "Tom";
	let number = 0;
</script>

Your name:  <input type="text" bind:value="{name}"/><br/>
Your favorite number: <input type="number" bind:value="{number}"/><br/><br/>

{#each Array(number) as x}
Hi {name}!&nbsp &nbsp 
{/each}
