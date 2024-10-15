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
        align-items: center;
        background: rgb(2,135,4);
        background: linear-gradient(90deg, rgb(1, 173, 116) 0%, rgb(29, 236, 194) 30%, rgb(148, 253, 221) 87%);
        color: rgb(235, 241, 231);
        text-shadow: 1px 1px 3px rgb(0, 46, 48);
    }
    img{
        height: 50px;
        width: 50px;
        padding-right: 1em;
    }
    ul{
        display: flex;   
        list-style: none;
        font-size: 0.8em;
    }
    ul li{     
        padding-inline: 1em;
        
    }
    ul li a{
        text-decoration: none; 
        color: #f4f1f1;
        font-weight: bold;
        background-color: rgb(2, 75, 57);
        border-radius: 0.5em;
        padding: 0.4em;
        padding-inline: 0.8em;
        border: 1px dotted rgb(148, 239, 219);
    }
    ul li a:hover{
        background-color: white;
        color: #333;
        border: 1px ridge black;
    }
  

</style>