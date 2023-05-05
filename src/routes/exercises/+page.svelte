<svelte:head>
  <title>MEV - Ejercicios</title>
</svelte:head>

<!-----------------------    Header ------------------------------------------------>

<section class="overflow-hidden bg-gray-50 grid md:grid-cols-2">
    <div class="p-8 md:p-12 lg:px-16 lg:py-24">
      <div class="mx-auto max-w-xl text-center sm:text-left">
        <h2 class="text-2xl font-bold text-gray-900 md:text-3xl">
            ACTIVIDAD FISICA
        </h2>
  
        <p class="flex text-gray-500 mt-4 md:block">
          La actividad física se refiere a cualquier movimiento del cuerpo que requiere un gasto de energía. 
          La actividad física es importante para mantener una buena salud física y mental.  
        </p>
        <p class="hidden text-gray-500 md:mt-4 md:block">
          Esto incluye actividades cotidianas como caminar, subir escaleras, hacer tareas domésticas
          y trabajar en el jardín, así como actividades deportivas y de ejercicios planificados como
          correr, nadar, levantar pesas, bailar y practicar deportes.    
        </p>
      </div>
    </div>
  
    <img
      alt="Ejercicios"
      src="/images/exercises1.jpg"
      class="h-56 w-full object-cover sm:h-full"
    />
  </section>

  <!---------------------- Section 1-------------------------------->

  <section>
    <div class="mx-auto max-w-screen-2xl px-4 py-16 sm:px-6 lg:px-8">
      <div class="grid grid-cols-1 lg:h-screen lg:grid-cols-2">
        <div class="relative z-10 lg:py-16">
          <div class="relative h-64 sm:h-80 lg:h-full">
            <img
              alt="Personas sentadas mirando television"
              src="/images/sitting-sm.jpg"
              class="absolute inset-0 h-full w-full object-cover"
            />
          </div>
        </div>
  
        <div class="relative flex items-center bg-gray-100">
          <span
            class="hidden lg:absolute lg:inset-y-0 lg:-left-16 lg:block lg:w-16 lg:bg-gray-100"
          ></span>
  
          <div class="p-8 sm:p-16 lg:p-24">
            <h2 class="text-2xl font-bold sm:text-3xl">
              Sedentarismo
            </h2>
  
            <p class="mt-4 text-gray-600">
              El sedentarismo es un estilo de vida en el que una persona no realiza actividad física
              suficiente o regular. Esto significa que la persona no gasta suficiente energía física
              en actividades cotidianas, como caminar, subir escaleras o hacer tareas domésticas,
              y tampoco realiza ejercicios físicos programados o deportes.
            </p>
           
          </div>
        </div>
      </div>
    </div>
  </section>

  <!------------------------------- Section 2 -------------------------------------->
  
  <section class="text-gray-600 body-font bg-slate-100">
    <div class="container px-5 py-24 mx-auto">
      <div class="xl:w-1/2 lg:w-3/4 w-full mx-auto text-center">
        <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="inline-block w-8 h-8 text-gray-400 mb-8" viewBox="0 0 975.036 975.036">
          <path d="M925.036 57.197h-304c-27.6 0-50 22.4-50 50v304c0 27.601 22.4 50 50 50h145.5c-1.9 79.601-20.4 143.3-55.4 191.2-27.6 37.8-69.399 69.1-125.3 93.8-25.7 11.3-36.8 41.7-24.8 67.101l36 76c11.6 24.399 40.3 35.1 65.1 24.399 66.2-28.6 122.101-64.8 167.7-108.8 55.601-53.7 93.7-114.3 114.3-181.9 20.601-67.6 30.9-159.8 30.9-276.8v-239c0-27.599-22.401-50-50-50zM106.036 913.497c65.4-28.5 121-64.699 166.9-108.6 56.1-53.7 94.4-114.1 115-181.2 20.6-67.1 30.899-159.6 30.899-277.5v-239c0-27.6-22.399-50-50-50h-304c-27.6 0-50 22.4-50 50v304c0 27.601 22.4 50 50 50h145.5c-1.9 79.601-20.4 143.3-55.4 191.2-27.6 37.8-69.4 69.1-125.3 93.8-25.7 11.3-36.8 41.7-24.8 67.101l35.9 75.8c11.601 24.399 40.501 35.2 65.301 24.399z"></path>
        </svg>
        <p class="leading-relaxed text-xl">
          Caminar es la mejor medicina para el hombre.
        </p>
        <span class="inline-block h-1 w-10 rounded bg-rose-500 mt-8 mb-6"></span>
        <h2 class="text-gray-900 font-medium title-font tracking-wider text-md">HIPÓCRATES DE COS</h2>
        <p class="text-gray-500">Antiguo Médico Griego</p>
      </div>
    </div>
  </section>

  <!---------------------------- Section 3 ------------------------------------------>

  <section class="text-gray-600 body-font">
    <div class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center">
      <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6 mb-10 md:mb-0">
        <img class="object-cover object-center rounded" alt="Paciente ECG" 
        src="/images/patient-ecg-sm.jpg">
      </div>
      <div class="lg:flex-grow md:w-1/2 lg:pl-24 md:pl-16 flex flex-col md:items-start md:text-left items-center text-center">
        <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-gray-900">Consulta a tu 
          <br class="hidden lg:inline-block">médico. 
        </h1>
        <p class="mb-8 leading-relaxed">
          Antes de comenzar a realizar actividad física consulte a su médico para realizar chequeos
          rutinarios. El profesional podrá evaluar tu estado de salud actual, realizar pruebas de
          diagnóstico y recomendarte las actividades físicas que son seguras y apropiadas para ti.</p>

          <p>
            Es importante tener en cuenta que algunos ejercicios pueden ser extenuantes y requieren una
            buena condición física. Si no estás acostumbrado a hacer ejercicio, es importante comenzar
            lentamente y aumentar gradualmente la intensidad y la duración de la actividad a medida que
            tu condición física mejora.
          </p>
        
      </div>
    </div>
  </section>
  
  <!-------------------------- Section 4 --------------------------------->

  <section class="text-gray-600 body-font">
    <div class="container px-5 md:py-20 mx-auto">
      <div class="text-center mb-20">
        <h1 class="sm:text-3xl text-2xl font-medium title-font text-gray-900 mb-4">
          Beneficios de la Actividad Física
        </h1>
        <p class="text-base leading-relaxed xl:w-2/4 lg:w-3/4 mx-auto text-gray-500s">
          Realizar actividad física regularmente tiene una amplia variedad de beneficios para nuestra
          salud y bienestar. Algunos de los principales son:
        </p>
        <div class="flex mt-6 justify-center">
          <div class="w-16 h-1 rounded-full bg-emerald-500 inline-flex"></div>
        </div>
      </div>
      <div class="flex flex-wrap sm:-m-4 -mx-4 -mb-10 -mt-4 md:space-y-0 space-y-6">
        <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
          <div class="w-20 h-20 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-5 flex-shrink-0">
            <img src="/images/heart-hand.svg" alt="Ilustración corazon manos" />
          </div>
          <div class="flex-grow">
            <h2 class="text-gray-900 text-lg title-font font-medium mb-3">
              Mejora la salud cardiovascular
            </h2>
            <p class="leading-relaxed text-base">
              Puede ayudar a mejorar la salud del corazón y reducir el riesgo de
              enfermedades cardiovasculares.
            </p>
            
          </div>
        </div>
        <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
          <div class="w-20 h-20 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-5 flex-shrink-0">
            <img src="/images/fitness.svg" alt="Piernas sobre una pelota de ejercicios"/> 
          </div>
          <div class="flex-grow">
            <h2 class="text-gray-900 text-lg title-font font-medium mb-3">
              Fortalecimiento muscular y óseo
            </h2>
            <p class="leading-relaxed text-base">
              Puede ayudar a aumentar la masa muscular y fortalecer los huesos,
              reduciendo el riesgo de caídas y fracturas.
            </p>
            
          </div>
        </div>
        <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
          <div class="w-20 h-20 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-5 flex-shrink-0">
            <img src="/images/men-jog.svg" alt="Hombre haciendo ejercicio"/> 
          </div>
          <div class="flex-grow">
            <h2 class="text-gray-900 text-lg title-font font-medium mb-3">
              Control del peso  
            </h2>
            <p class="leading-relaxed text-base">
              La actividad física regular puede ayudar a quemar calorías y mantener un peso saludable.
            </p>
            
          </div>
        </div>
      </div>
      
    </div>
  </section>
  

  <!---------------------------- Section 5 --------------------------------->

  <section class="text-gray-600 body-font">
    <div class="container px-5 py-24 mx-auto">
      <div class="flex items-center lg:w-3/5 mx-auto border-b pb-10 mb-10 border-gray-200 sm:flex-row flex-col">
        <div class="h-20 w-20 sm:mr-10 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 flex-shrink-0">
          <img src="/images/brain2.svg" alt="Imagen de un cerecbro" />
        </div>
        <div class="flex-grow sm:text-left text-center mt-6 sm:mt-0">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-2">
            Mejora la salud mental
          </h2>
          <p class="leading-relaxed text-base">
            Puede ayudar a reducir el estrés, la ansiedad y la depresión, mejorando la salud mental y
            el bienestar general.
          </p>
          
        </div>
      </div>
      <div class="flex items-center lg:w-3/5 mx-auto border-b pb-10 mb-10 border-gray-200 sm:flex-row flex-col">
        <div class="flex-grow sm:text-left text-center mt-6 sm:mt-0">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-2">
            Reducción del riesgo de enfermedades crónicas
          </h2>
          <p class="leading-relaxed text-base">
            Puede reducir el riesgo de enfermedades crónicas como la diabetes tipo 2, la osteoporosis
            y ciertos tipos de cáncer.
          </p>
         
        </div>
        <div class="sm:order-none order-first h-20 w-20 sm:ml-10 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 flex-shrink-0">
          <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-16 h-16" viewBox="0 0 24 24">
            <image xlink:href="/images/ribbon1.svg" width="25" height="25"/>
          </svg>
        </div>
      </div>
      <div class="flex items-center lg:w-3/5 mx-auto sm:flex-row flex-col">
        <div class="h-20 w-20 sm:mr-10 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 flex-shrink-0">
          <img src="/images/lung.svg" alt="Pulmones" />
        </div>
        <div class="flex-grow sm:text-left text-center mt-6 sm:mt-0">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-2">
            Mejora la salud pulmonar
          </h2>
          <p class="leading-relaxed text-base">
            Puede mejorar la capacidad pulmonar y la función respiratoria.
          </p>
          
        </div>
      </div>
      
    </div>
  </section>