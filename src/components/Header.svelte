<script>
   let isMenuOpen = false;

   const toggleMenu = () => {
      isMenuOpen = !isMenuOpen;
   }
</script>

<header class="px-4 py-5 flex items-center justify-between">
   <div>
      <a href="/">
         <img class="h-10" src="./img/logo.svg" alt="Tuple Logo">
      </a>
   </div>

   <div>
      <button on:click={ () => toggleMenu() } class="focus:outline-none">
         <svg viewBox="0 0 20 20" fill="currentColor" class="text-gray-700 w-6 h-6"><path fill-rule="evenodd" d="M3 7a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 13a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd"></path></svg>
      </button>
   </div>

   <div class="absolute inset-0 {isMenuOpen ? 'block' : 'hidden'} block">
      <div class="fixed w-full h-screen bg-black inset-0 z-10 bg-opacity-50"></div>
      <div class="m-4 z-20 p-6 relative bg-white rounded-lg">
         <div class="flex mb-4 items-center justify-between">
            <span class="text-gray-600 text-sm">Navigation</span>
            
            <button on:click={ () => toggleMenu() } class="focus:outline-none">
               <svg viewBox="0 0 20 20" fill="currentColor" class="x w-4 h-4"><path fill-rule="evenodd" d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z" clip-rule="evenodd"></path></svg>
            </button>
         </div>
         <a class="block mt-6 text-gray-900 text-lg font-normal" href="#">Pricing</a>
         <a class="block mt-6 text-gray-900 text-lg font-normal" href="#">Pairing Guide</a>
         <a class="block mt-6 text-gray-900 text-lg font-normal" href="#">Jobs</a>
         <a class="block mt-6 text-gray-900 text-lg font-normal" href="#">Docs</a>
         <a class="block mt-6 text-gray-900 text-lg font-normal" href="#">Blog</a>
         <a class="block mt-6 text-gray-900 text-lg font-normal" href="#">Sign In</a>
         <a class="block mt-8 p-2 text-white bg-indigo-600 text-center rounded-lg font-semibold" href="#">Sign Up</a>
      </div>
   </div>

</header>