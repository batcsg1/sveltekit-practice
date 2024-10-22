<script>
    import Footer from "$lib/Footer.svelte";
</script>

<slot/> <!--Imports stuff from main page (e.g the header)-->
<Footer></Footer>

<style>
    :global(*) {
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
</style>

