<script>
    let isOpen = false

    function handleMenu(){
        isOpen = !isOpen
    }
</script>


<nav class="border-gray-200 px-2 sm:px-4 py-2.5 rounded bg-gradient-to-r from-teal-500 to-green-500">
    <div class="container flex flex-wrap items-center justify-between mx-auto">
      <a href="/" class="flex items-center">
          <img src="/images/mev-logo.svg" class="h-8 mr-3 sm:h-14" alt="MEV Logo" />
          <span class="self-center text-xl font-semibold whitespace-nowrap">
            MEV
          </span>
      </a>
      <button data-collapse-toggle="navbar-default" type="button" on:click={handleMenu}
      class="inline-flex items-center p-2 ml-3 text-sm text-gray-500 rounded-lg md:hidden focus:outline-none focus:ring-2" aria-controls="navbar-default" aria-expanded="false">
        <span class="sr-only">Open main menu</span>
        <svg class="w-6 h-6" aria-hidden="true" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd"></path></svg>
      </button>
      <div class="{isOpen ? 'block' : 'hidden'} w-full md:block md:w-auto" id="navbar-default">
        <ul class="flex flex-col p-4 mt-4 border border-gray-100 rounded-lg md:flex-row md:space-x-8 md:mt-0 md:text-sm md:font-medium md:border-0">
          <li>
            <a href="/nutrition" class="links">Nutrición</a>
          </li>
          <li>
            <a href="/exercises" class="links">Ejercicios</a>
          </li>
          <li>
            <a href="/stress" class="links">Estrés</a>
          </li>
          <li>
            <a href="/sleep" class="links">Sueño</a>
          </li>
          <li>
            <a href="/relation" class="links">Conexiones</a>
          </li>
          <li>
            <a href="/toxic" class="links">Tóxicos</a>
          </li>
          
        </ul>
      </div>
    </div>
  </nav>
  

  <style lang="postcss">
    .links {
      @apply block text-lg py-2 pl-3 pr-4 text-gray-700 rounded 
      md:bg-transparent md:border-0 md:hover:text-rose-700 md:p-0
    }
  </style>