<script>
    let count = 0;
	const increment = () => {
		count += 1;
	};
</script>

<style>

</style>

<button on:click={increment}>
    count: {count}
</button>