<script>
    export let data;
    let { user_needs } = data;
</script>

<h1>User Needs</h1>
<div>
    {#each user_needs as un}
        <h3>{un.title}</h3>
        <p>{un.description}</p>
    {/each}
</div>
