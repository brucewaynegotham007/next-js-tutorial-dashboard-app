<main>
    <div>
        {#each Array(3) as _}
            <div>
                {#each Array(3) as _}
                    <button onclick={() => {}} aria-label="Cell"></button>
                {/each}
            </div>
        {/each}
    </div>
</main>

