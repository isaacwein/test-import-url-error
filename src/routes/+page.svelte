<script lang="ts">
    import testCSS from './test.css?url'
    console.log(testCSS)
</script>
<svelte:head>
    <link rel="stylesheet" href="{testCSS}">
</svelte:head>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
