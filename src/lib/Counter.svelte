<script>
    let count = 0;
    function incrementCount(){
        count++;
    }
</script>
    <button on:click={incrementCount}>Add +1</button>
    <p>Count: {count}</p>
<style>

</style>