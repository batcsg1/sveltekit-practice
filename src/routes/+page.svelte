<script>
    import Footer from '$lib/Footer.svelte';
    import Header from '$lib/Header.svelte';
    import Peter from '$lib/img/peter.jpeg';
</script>

<!-- <h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p> -->

<Header headingTitle = "[chatgpt.com]"></Header>

<div>
    <h2>Frameworks are the bomb, bro!</h2>
</div>

<Footer year={2025} img ={Peter} alt="Peter"/>

<style>
    :global(*){
        font-family: sans-serif;
    }
    :global(body){
        padding: 4em;
    }
   
</style>