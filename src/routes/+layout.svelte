<script>

 import "@picocss/pico/css/pico.css";
import "../app.css";
</script>


<header>

<nav class=" border-gray-200 px-2 sm:px-4 py-2.5  bg-gray-800">
     <div class="container flex flex-wrap items-center justify-between mx-auto">
       <a href="/" class="flex items-center">
           <img src="https://flowbite.com/docs/images/logo.svg" class="h-6 mr-3 sm:h-9" alt="Flowbite Logo" />
           <span class="self-center text-xl font-semibold whitespace-nowrap text-white ">Sreenidhi Technetium</span>
       </a>
       <button data-collapse-toggle="navbar-default" type="button" class="inline-flex items-center p-2 ml-3 text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200" aria-controls="navbar-default" aria-expanded="false">
         <span class="sr-only">Open main menu</span>
         <svg class="w-6 h-6" aria-hidden="true" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd"></path></svg>
       </button>
       <div class="hidden w-full md:block md:w-auto" id="navbar-default">
         <ul class="flex flex-col p-4 mt-4 border  rounded-lg  md:flex-row md:space-x-8 md:mt-0 md:text-sm md:font-medium md:border-0    bg-gray-800 md:   border-gray-700">
           <li>
               <a href="/" class="block py-2 pl-3 pr-4   rounded  md:border-0  md:p-0   text-gray-400 md:  hover:text-white   hover:bg-gray-700 md:  hover:bg-transparent">Home</a>
           </li>
           <li>
             <a href="/team" class="block py-2 pl-3 pr-4   rounded md:border-0  md:p-0   text-gray-400 md:  hover:text-white   hover:bg-gray-700 md:  hover:bg-transparent">Team</a>
           </li>
           <li>
             <a href="#!" class="block py-2 pl-3 pr-4   rounded md:border-0  md:p-0   text-gray-400 md:  hover:text-white   hover:bg-gray-700 md:  hover:bg-transparent">Services</a>
           </li>
           <li>
             <a href="#!" class="block py-2 pl-3 pr-4   rounded md:border-0 md:p-0   text-gray-400 md:  hover:text-white   hover:bg-gray-700 md:  hover:bg-transparent">Pricing</a>
           </li>
           <li>
             <a href="#!" class="block py-2 pl-3 pr-4   rounded  md:border-0 md:p-0   text-gray-400 md:  hover:text-white   hover:bg-gray-700 md:  hover:bg-transparent">Contact</a>
           </li>
         </ul>
       </div>
     </div>
   </nav>
   
</header>

<slot/>

<div class ="bg-gray-800   ">
     <footer class =" py-12 text-right px-24"> 
     <a class=" text-gray-400" href="/">Technetium 2023.</a>
     <p>
     Made with SvelteKit 
     </p>
     </footer>
</div>


<style>
    
    header {
        display: grid;

        place-items: left;
      }
      body { min-height: 1200vh; }

    
 
 </style>