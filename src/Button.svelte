<script>
    export let count;
    
	export let handleClick = () => {
        count += 1;
    };
</script>

<style>

</style>

<button on:click={handleClick}>
    count: {count}
</button>