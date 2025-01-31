<script>
    import Tictactoe from "./tictactoe.svelte";

</script>
<!-- <script>
    let name = '';
    let showGreeting = false;
</script>

<main>
    <h1>Hello Svelte!</h1>
    
    <input 
        bind:value={name} 
        placeholder="Enter your name"
    />
    
    <button on:click={() => showGreeting = true}>
        Greet Me
    </button>

    {#if showGreeting && name}
        <p>Welcome, {name}! 👋</p>
    {/if}
</main>

<style>
    main {
        padding: 2rem;
        max-width: 600px;
        margin: 0 auto;
    }

    input {
        padding: 8px;
        margin-right: 10px;
    }

    button {
        padding: 8px 16px;
        background: #ff3e00;
        color: white;
        border: none;
        border-radius: 4px;
        cursor: pointer;
    }
</style> -->

<Tictactoe />

