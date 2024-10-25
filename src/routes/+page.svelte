<script>
  import Header from "$lib/Header.svelte";
  import Main from "$lib/Main.svelte";
  export let data;
  console.log(data.posts);
</script>

<Header headingTitle = "chatgpt.com"></Header>

<Main mainTitle = "Welcome to ChatGPT!"></Main>

