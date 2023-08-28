<script>
import IconButton from '$lib/components/IconButton.svelte';
export let data;
</script>

<div class="sidebar">
{#each data as icon}
    <IconButton {icon}/>
{/each}
</div>