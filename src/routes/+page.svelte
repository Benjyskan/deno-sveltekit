<script lang="ts">
	let count = 0;

	const add = () => {
		count = count + 1;
	};
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
<p>count: {count}</p>
<button on:click={add}>+</button>
