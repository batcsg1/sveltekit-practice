<script>
    export let headingTitle;
    import Logo from '$lib/img/chatgpt.webp';
</script>

<header>    
    <img src="{Logo}" alt="logo" width=100px height=100px>
    <h1>{headingTitle}</h1>
    <nav>
        <ul>
            <li><a href="/">Login</a></li>
            <li><a href='/about'>Register</a></li>
            <li><a href='/contact'>About</a></li>
        </ul>
    </nav>
</header>

<style>
    header{
        display: flex;
        justify-content: center;
        background: rgb(2,135,4);
        background: linear-gradient(90deg, rgb(9, 201, 12) 0%, rgb(122, 247, 126) 30%, rgb(148, 253, 192) 87%);
        color: rgb(235, 241, 231);
        text-shadow: 1px 1px 3px rgb(4, 48, 0);
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
        padding-inline: 3em;
        padding-block: 1em;  
    }
    ul li a{
        text-decoration: none; 
        font-family: Arial, Helvetica, sans-serif;
        color: #f8f7f7;
        text-shadow: 3px 1px 3px black;
    }
  

</style>