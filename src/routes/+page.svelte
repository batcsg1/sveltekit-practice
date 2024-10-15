<script>
    import Footer from '$lib/Footer.svelte';
    import Header from '$lib/Header.svelte';
    // import Peter from '$lib/img/peter.jpeg';
    import Main from '$lib/Main.svelte';
</script>

<!-- <h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p> -->

<Header headingTitle = "[chatgpt.com]"></Header>

<Main mainTitle = "[Welcome to ChatGPT]"></Main>

<Footer year={2025}/>

<style>
    :global(*){
        font-family: Verdana, Geneva, Tahoma, sans-serif;
    }
    /* :global(body){
        padding: 4em;
    } */  
</style>