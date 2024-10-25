<script>
    export let mainTitle;
</script>

    <header>Welcome to ChatGPT!</header>
    <h1>{mainTitle}</h1>

    <main>
        <h2>ChatGPT is an online chatbot that can respond to human input</h2>
        <p>You can use ChatGPT to:</p>
        <ul>
            <li>Come up with a cake recipe</li>
            <li>Learn a new language</li>
            <li>Design a game</li>
            <li>Create jokes</li>
        </ul>
        <p>To get started, click below to register, if you have already registered, you can login.</p>

        <section>
            <button>Register</button>
            <button>Login</button>
        </section>
    </main>


<style>

    header{
        background-color: rgb(2, 75, 52);
        color: white;
        padding: 0.5em;
    }
    h1{
        font-size: 1em;
        text-align: center;
    }
    *{
        font-size: 0.9em;  
    }
    section{
        display: flex;
        justify-content: center;
    }
    section *{
        padding-inline: 2em;
        margin-inline: 3em;
        color: white;
    }
    button{
        background-color: rgb(66, 160, 140)  
    }

</style>