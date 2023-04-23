<script lang="ts">
    let count: number = 0;

    function IncrementCount() {
        count++;
    }

    function DecrementCount() {
        count--;
    }
</script>

<h1>Welcome to SvelteKit</h1>
<button on:click={IncrementCount}>CLICK ME</button>
<button on:click={DecrementCount}>do not click me</button>
<p>{count}</p>
