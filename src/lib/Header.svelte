<script>
    export let headingTitle;

</script>

<header>    
    <h1>{headingTitle}</h1>
    <nav>
        <ul>
            <li><a href="/">Home</a></li>
            <li><a href='/about'>About</a></li>
            <li><a href="/">Website</a></li>
        </ul>
    </nav>
</header>

<style>
    header{
        display: flex;
        justify-content: center;
    }
    h1{
        display: grid;
        align-items: center;
    }
    ul{
        display: flex;
        justify-content: space-around;
        list-style: none;
        font-size: 1.5em;
    }
    ul li{
        background-color: yellow;      
        padding-inline: 3em;
        padding-block: 1em;
        border: 2px solid black;
        
    }
    ul li a{
        text-decoration: none; 
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        color: #333;
    }
  

</style>