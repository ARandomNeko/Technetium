<script>

  import "@picocss/pico/css/pico.css";
  import "../app.css";
  import "flowbite/dist/flowbite.css";
</script>
<link rel="stylesheet" href="https://cdn.materialdesignicons.com/6.5.95/css/materialdesignicons.min.css">

<header class="py-12 ">

  <nav class=" px-2 sm:px-4 py-2.5 bg-gray-900 fixed w-full z-20 top-0 left-0 border-b border-gray-600">
    <div class="container flex flex-wrap items-center justify-between mx-auto">
    <a href="https://flowbite.com/" class="flex items-center">
        <img src="https://flowbite.com/docs/images/logo.svg" class="h-6 mr-3 sm:h-9" alt="Flowbite Logo">
        <span class="self-center text-xl font-semibold whitespace-nowrap text-white">Technetium</span>
    </a>
    
    <div class="items-center justify-between  w-full md:flex md:w-auto md:order-1" id="navbar-default">
      <ul class="flex  p-4   rounded-lg flex-row space-x-8 mt-0 text-sm font-medium border-0 bg-gray-900 ">
        <li>
          <a href="/" class="block py-2 pl-3 pr-4 text-gray-400 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-white dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Home</a>
        </li>
        <li>
          <a href="/team" class="block py-2 pl-3 pr-4 text-gray-400 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-white dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Team</a>
        </li>
        <li>
          <a href="/about" class="block py-2 pl-3 pr-4 text-gray-400 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-white dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">About</a>
        </li>
        <li>
          <a href="#!" class="block py-2 pl-3 pr-4 text-gray-400 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-white dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Register</a>
        </li>
      </ul>
    </div>
    </div>
  </nav>
   
</header>

<slot/>

<footer class =" py-12 justify-items-center px-24 border-gray-600 bg-gray-900 "> 
  <div class="grid md:grid-cols-2 md:justify-items-center">
  <div>
    <h1 class="text-4xl md:text-5xl xl:text-6xl  tracking-tight font-semibold text-white font-mono mb-1">
      Contact Us
    </h1>

    <h1 class="text-3xl md:text-4xl xl:text-5xl  tracking-tight font-semibold text-blue-500 mb-1">
      Technetium@sis.edu.in
    </h1>

    <div class="flex items-center justify-left  hover:opacity-100
    transition-opacity duration-300 py-8">

        <!-- Linkedin -->
        <a href=" https://github.com/ARandomNeko" class="flex rounded-2xl hover:bg-indigo-50 h-10 w-10  scale-125">
            <i class="mdi mdi-github text-indigo-500 mx-auto mt-2"></i>
        </a>



        <!-- Instagram -->
        <a href=" https://www.instagram.com/arandomneko21/" class="flex rounded-2xl hover:bg-orange-100 h-10 w-10 translate-x-4 scale-125">
            <i class="mdi mdi-instagram text-orange-400 mx-auto mt-2"></i>
        </a>
    </div>
 
  </div>
  <div>
    <ul class="text-gray-300 text-2xl">
      <li class="mb-4">
          <a href="/" class=" hover:underline">Home</a>
      </li>
      <li class="mb-4">
          <a href="/team" class="hover:underline">Team</a>
      </li>
      <li class="mb-4">
          <a href="/about" class="hover:underline">About</a>
      </li>
      <li class="mb-4">
          <a href="#!" class="hover:underline">Register</a>
      </li>
  </ul>

  </div>
  </div>

     <div class="grid md:grid-cols-2 lg:px-24">
      <div class="justify-items-start">
      <a class=" text-gray-400  " href="/">Technetium 2023.</a>
      <p>
      By Rituparan Reddy 
      </p>
      </div>
      
    </div>  
</footer>



