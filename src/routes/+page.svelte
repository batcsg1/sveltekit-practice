<script>
  import Header from "$lib/Header.svelte";
  import Main from "$lib/Main.svelte";
  import Posts from "$lib/Posts.svelte";
  export let data;
  const posts = data.posts;

</script>

<Header headingTitle = "chatgpt.com"></Header>

<Main mainTitle = "Welcome to ChatGPT!"></Main>
<h2>Random posts</h2>
{#each posts as post}
    <Posts {post}/>
{/each}


<style>
    
</style>

