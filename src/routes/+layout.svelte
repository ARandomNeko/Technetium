<script>
    import pico from "@picocss/pico"
</script>
<nav>
    <a prefetch href="/"> My site</a>
</nav>


<slot/>


<footer> Technetium 2023</footer>

<style>
    nav{
        background : (0, 0, 0, 0.4);
        padding-top: 1rem;
        padding-bottom: 1rem;
        letter-spacing: 0.1px;
        font-weight: 500;
}
</style>