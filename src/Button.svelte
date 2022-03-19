<script>
    export let count;
    
	export let increment;
</script>

<style>

</style>

<button on:click={increment}>
    count: {count}
</button>