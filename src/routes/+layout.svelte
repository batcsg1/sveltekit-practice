<script>
    import Header from "$lib/Header.svelte";
    import Footer from "$lib/Footer.svelte";
</script>

<Header headingTitle = "chatgpt.com"></Header>

<slot/> <!--Imports stuff from main page (e.g the header)-->

<Footer></Footer>

<style>
    :global(*){
        font-family: Verdana, Geneva, Tahoma, sans-serif;
    }   
</style>

