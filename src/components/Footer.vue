<template>
    <footer id="footer">
        <p>Make Your Burger &copy;  
            <a id="link" href="https://www.linkedin.com/in/rodrigolc/" target="_blank"> 
                Rodrigo Carvalho 2023   
            </a>  
        </p>
    </footer>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style scoped>
    #footer {
        height: 200px;
        background-color: #222;
        border-top: 4px solid #111;
        color: #FCBA03;
        display: flex;
        align-items: center;
        justify-content: center;
        bottom: 0;
        width: 100%;
    }
    #link {
        color: #FCBA03;
        text-decoration: none;
    }

    #link:hover {
        color: aliceblue;
    }
</style>