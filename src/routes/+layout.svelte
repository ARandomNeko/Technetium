<script>
 import pico from "@picocss/pico"
</script>
<nav class="container mx-auto">
    <a href="/"> My site</a>
</nav>


<slot/>

<div class=" container mx-auto text-right">
     <footer> Technetium 2023</footer>
</div>


<style>
    nav{
        background : (0, 0, 0, 0.4);
        padding-top: 1rem;
        padding-bottom: 1rem;
        
        letter-spacing: 0.1px;
        font-weight: 500;
}
</style>