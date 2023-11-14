<script>
    import hero_image from '$lib/images/hero-image.jpg';
    import Table from '$lib/components/Table.svelte'
    import Header from '$lib/components/Header.svelte';

    let columns = ['Name', 'Age', 'Country','Bus'];
  let data = [
    { id: 1, Name: 'John Doe', Age: 30, Country: 'USA' },
    { id: 2, Name: 'Jane Doe', Age: 25, Country: 'Canada' },
    { id: 3, Name: 'Bob Smith', Age: 35, Country: 'UK' },
  ];
</script>

<svelte:head>
    <title>Home</title>
    <meta name="description" content="Bus" />
</svelte:head>

<Header />

<img class="hero-img" src={hero_image} alt="Welcome" />

<h1>SCHEDULE <br>Live bus travel information</h1>

<Table {columns} {data} />

<style>
    .hero-img {
        width: 100%;
        height: 640px;
    }
</style>
