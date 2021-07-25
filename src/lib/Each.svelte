<script>
	let cats = [
	  { id: "J---aiyznGQ", name: "Keyboard Cat" },
	  { id: "z_AbfPXTKms", name: "Maru" },
	  { id: "OUtn3pvWmpg", name: "Henri The Existential Cat" }
	];
</script>

<h3>The Famous Cats of YouTube</h3>

<ul>
{#each cats as cat, i}
		<li><a target="_blank" href="https://www.youtube.com/watch?v={cat.id}">
			{cat.name} = {i}
		</a></li>
{/each}
</ul>

<ul>
{#each cats as { id, name }, i}
		<li><a target="_blank" href="https://www.youtube.com/watch?v={id}">
			{name} = {id} = {i}
		</a></li>
{/each}
</ul>
