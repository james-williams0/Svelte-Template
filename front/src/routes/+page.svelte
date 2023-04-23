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
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
<button on:click={IncrementCount}>CLICK ME</button>
<button on:click={DecrementCount}>do not click me</button>
<p>{count}</p>
