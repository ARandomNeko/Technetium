<script>
 // @ts-ignore
 import pico from "@picocss/pico"
 let typeEffect = 'typing-dmeo'
</script>
<nav class="container mx-auto">
    <div class="navbar-collapse collapse grow items-center" id="navbarSupportedContentY">
        <ul class="navbar-nav mr-auto lg:flex lg:flex-row">
          <li class="nav-item">
            <a class="nav-link block pr-2 lg:px-2 py-2 text-gray-600 hover:text-gray-700 focus:text-gray-700 transition duration-150 ease-in-out" href="#!" data-mdb-ripple="true" data-mdb-ripple-color="light">Dashboard</a>
          </li>
          <li class="nav-item">
            <a class="nav-link block pr-2 lg:px-2 py-2 text-gray-600 hover:text-gray-700 focus:text-gray-700 transition duration-150 ease-in-out" href="#!" data-mdb-ripple="true" data-mdb-ripple-color="light">Team</a>
          </li>
          <li class="nav-item mb-2 lg:mb-0">
            <a class="nav-link block pr-2 lg:px-2 py-2 text-gray-600 hover:text-gray-700 focus:text-gray-700 transition duration-150 ease-in-out" href="#!" data-mdb-ripple="true" data-mdb-ripple-color="light">Projects</a>
          </li>
        </ul>
      </div>
</nav>


<slot/>

<div class=" container mx-auto text-right">
     <footer class=""> Technetium 2023</footer>
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