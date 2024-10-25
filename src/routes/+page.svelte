<script>
  import Header from "$lib/Header.svelte";
  import Main from "$lib/Main.svelte";
  export let data;
  const posts = data.posts;

</script>

<Header headingTitle = "chatgpt.com"></Header>

<Main mainTitle = "Welcome to ChatGPT!"></Main>
<h2>Random posts</h2>
{#each posts as post }
    <article>
        <h3>{post.title}</h3>
        <p>{post.body}</p>
    </article>
{/each}

<style>
    article{
        background-color: rgb(228, 216, 216);
        padding: 0.5em ;
        margin: 1em;
    }
</style>

