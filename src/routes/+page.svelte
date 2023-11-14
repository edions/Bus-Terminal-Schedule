<script>
    import hero_image from '$lib/images/hero-image.jpg';
</script>

<svelte:head>
    <title>Home</title>
    <meta name="description" content="Bus" />
</svelte:head>

<img class="hero-img" src={hero_image} alt="Welcome" />

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<style>
    .hero-img {
        width: 100%;
        height: 500px;
    }
</style>
