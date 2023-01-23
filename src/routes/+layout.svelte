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

       <div class=" w-full md:block md:w-auto" id="navbar-default">
         <ul class="flex flex-row   rounded-lg  md:flex-row md:space-x-8 md:mt-0 md:text-sm md:font-medium md:border-0    bg-gray-800 md:   border-gray-700 translate-y-2">
           <li>
               <a href="/" class="block py-2 pl-3 pr-4   rounded  md:border-0  md:p-0   text-gray-400 md:  hover:text-white   hover:bg-gray-700 md:  hover:bg-transparent">Home</a>
           </li>
           <li>
             <a href="/team" class="block py-2 pl-3 pr-4   rounded md:border-0  md:p-0   text-gray-400 md:  hover:text-white   hover:bg-gray-700 md:  hover:bg-transparent">Team</a>
           </li>
           <li>
             <a href="/itinerary" class="block py-2 pl-3 pr-4   rounded md:border-0  md:p-0   text-gray-400 md:  hover:text-white   hover:bg-gray-700 md:  hover:bg-transparent">Itinerary</a>
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


    
 
 </style>