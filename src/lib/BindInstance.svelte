<script>
	import InputField from './BindInstanceInput.svelte';

	let field;
</script>

<InputField bind:this={field}/>

<button on:click={() => field.focus()}>Focus field</button>
