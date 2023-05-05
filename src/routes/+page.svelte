<svelte:head>
  <title>MEV - Inicio</title>
</svelte:head>

<!-- Header  -->
<section class="relative header-page">
  <div class="absolute inset-0 bg-white/75 sm:bg-transparent sm:bg-gradient-to-r sm:from-white/95 sm:to-white/25"></div>

  <div class="relative z-10 mx-auto max-w-screen-xl px-4 py-32 sm:px-6 lg:flex lg:h-screen lg:items-center lg:px-8">
    <div class="max-w-xl text-center sm:text-left">
      <h1 class="text-3xl font-extrabold sm:text-5xl">
        Medicina del
        <strong class="block font-extrabold text-rose-700">
          Estilo de Vida.
        </strong>
      </h1>
      <p class="mt-4 max-w-lg sm:text-xl sm:leading-relaxed">
        Enfoque basado en evidencia que busca prevenir, tratar e incluso revertir enfermedades crónicas
        reemplazando conductas no saludables por aquellas que si lo son.
      </p>
    </div>
  </div>

  <div class="absolute inset-0 z-0">
    <video autoplay muted loop class="w-full h-full object-cover">
      <source src="/videos/MedicinaEstiloVida-720.mp4" type="video/mp4" />
    </video>
  </div>
</section>

<!-------------------------Section 1----------------------------->

<section class="md:my-16">
  <div class="mx-auto max-w-screen-2xl px-4 py-8 sm:px-6 lg:px-8">
    <div class="grid grid-cols-1 gap-4 md:grid-cols-2">
      <div class="bg-emerald-200 p-8 md:p-12 lg:px-16 lg:py-24">
        <div class="mx-auto max-w-xl text-center">
          <h2 class="text-1xl font-bold  md:text-2xl">
            Disciplina médica que se enfoca en prevenir y tratar enfermedades crónicas a
            través de cambios en el estilo de vida de los pacientes.
          </h2>

          <p class="hidden sm:mt-4 sm:block">
            La medicina del estilo de vida se basa en la idea de que muchos de los problemas de salud
            que enfrenta la población actual son el resultado de factores relacionados con el estilo de
            vida, como la dieta, el ejercicio físico, la gestión del estrés y otros hábitos cotidianos.
          </p>

          
        </div>
      </div>

      <div class="grid grid-cols-2 gap-4 md:grid-cols-1 lg:grid-cols-2">
        <img
          alt="Good Nutrition"
          src="/images/nutrition-sm.jpg"
          class="h-40 w-full object-cover sm:h-56 md:h-full"
        />

        <img
          alt="Exercises"
          src="/images/exercises-sm.jpg"
          class="h-40 w-full object-cover sm:h-56 md:h-full"
        />
      </div>
    </div>
  </div>
</section>

<!-------------------------Section 2----------------------------->

<section class="text-gray-600 body-font">
  <div class="container px-5 py-8 md:py-24 mx-auto">
    <div class="xl:w-1/2 lg:w-3/4 w-full mx-auto text-center">
      <img src="/images/health-care-diet.svg" alt="health care diet" 
      class="inline-block w-16 h-16 mb-8"/>
      
      <p class="leading-relaxed text-lg">
        Los profesionales de la medicina del estilo de vida trabajan con los pacientes para identificar
        áreas de su estilo de vida que pueden ser modificadas para mejorar su salud. Por ejemplo,
        pueden proporcionar recomendaciones nutricionales, prescribir ejercicios físicos, enseñar
        técnicas de relajación y manejo del estrés, y fomentar cambios en los patrones de sueño y en
        los hábitos de consumo de tabaco y alcohol. También pueden ayudar a los pacientes a establecer
        objetivos realistas para lograr un estilo de vida más saludable y brindar apoyo y motivación
        para alcanzar esos objetivos.
      </p>
      <span class="inline-block h-1 w-16 rounded bg-emerald-500 mt-8 mb-6"></span>
      
    </div>
  </div>
</section>

<!-------------------------Section 3----------------------------->


<section class="text-gray-600 body-font">
  <div class="container px-5 md:py-12 mx-auto">
    <div class="text-center mb-20">
      <h1 class="sm:text-3xl text-2xl font-medium title-font text-gray-900 mb-4">
        Los 6 pilares de la medicina del estilo de vida.
      </h1>
      <p class="text-base leading-relaxed xl:w-2/4 lg:w-3/4 mx-auto text-gray-500s">
        Disciplina integradora que aborda a los pacientes en su totalidad, considerando todos los
        aspectos de su vida que puedan afectar su salud. Perspectiva de salud y bienestar
        holístico que se enfoca en prevenir enfermedades antes de que se desarrollen, promoviendo
        la salud y la calidad de vida de las personas.
      </p>
      <div class="flex mt-6 justify-center">
        <div class="w-16 h-1 rounded-full bg-emerald-500 inline-flex"></div>
      </div>
    </div>
    <div class="flex flex-wrap sm:-m-4 -mx-4 -mb-10 -mt-4 md:space-y-0 space-y-6">
      <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
        <div class="w-20 h-20 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-5 flex-shrink-0">
          <img src="/images/organic-nutrition.svg" alt="Organic Nutrition"/>
        </div>
        <div class="flex-grow">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-3">Nutrición</h2>
          <p class="leading-relaxed text-base">
            Una nutrición saludable es aquella en la que se consumen los nutrientes necesarios en
            cantidades adecuadas para mantener una buena salud.
          </p>
          <a href="/nutrition" class="mt-3 text-indigo-500 inline-flex items-center">Aprende más
            <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-2" viewBox="0 0 24 24">
              <path d="M5 12h14M12 5l7 7-7 7"></path>
            </svg>
          </a>
        </div>
      </div>
      <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
        <div class="w-20 h-20 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-5 flex-shrink-0">
          <img src="/images/exercise-autumn.svg" alt="Ejercicio" />
        </div>
        <div class="flex-grow">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-3">Ejercicios</h2>
          <p class="leading-relaxed text-base">
            Práctica regular y estructurada de actividades físicas que tengan como objetivo mejorar la
            salud física y mental en general.  
          </p>
          <a href="/exercises" class="mt-3 text-indigo-500 inline-flex items-center">Aprende más
            <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-2" viewBox="0 0 24 24">
              <path d="M5 12h14M12 5l7 7-7 7"></path>
            </svg>
          </a>
        </div>
      </div>
      <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
        <div class="w-20 h-20 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-5 flex-shrink-0">
          <img src="/images/meditation.svg" alt="Meditación"/>
        </div>
        <div class="flex-grow">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-3">Stress</h2>
          <p class="leading-relaxed text-base">
            La gestión del estrés se refiere a las estrategias y técnicas utilizadas para ayudar a reducir
            los niveles de estrés en una persona.   
          </p>
          <a href="/stress" class="mt-3 text-indigo-500 inline-flex items-center">Aprende más
            <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-2" viewBox="0 0 24 24">
              <path d="M5 12h14M12 5l7 7-7 7"></path>
            </svg>
          </a>
        </div>
      </div>
    </div>
  </div>

  <div class="container px-5 py-12 mx-auto">
    <div class="flex flex-wrap sm:-m-4 -mx-4 -mb-10 -mt-4 md:space-y-0 space-y-6">
      <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
        <div class="w-20 h-20 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-5 flex-shrink-0">
          <img src="images/sleep-face.svg" alt="Cara de dormido" />
        </div>
        <div class="flex-grow">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-3">Sueño</h2>
          <p class="leading-relaxed text-base">
            El sueño reparador se refiere a la cantidad y calidad de sueño necesarios para reparar y
            restaurar el cuerpo y la mente. 
          </p>
          <a href="/sleep" class="mt-3 text-indigo-500 inline-flex items-center">Aprende más
            <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-2" viewBox="0 0 24 24">
              <path d="M5 12h14M12 5l7 7-7 7"></path>
            </svg>
          </a>
        </div>
      </div>
      <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
        <div class="w-20 h-20 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-5 flex-shrink-0">
          <img src="/images/people-support.svg" alt="Icono con Personas" />
        </div>
        <div class="flex-grow">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-3">Conexiones</h2>
          <p class="leading-relaxed text-base">
            Las conexiones sociales positivas pueden mejorar la salud física al fortalecer el sistema inmunológico y aumentar la longevidad.
          </p>
          <a href="/relation" class="mt-3 text-indigo-500 inline-flex items-center">Aprende más
            <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-2" viewBox="0 0 24 24">
              <path d="M5 12h14M12 5l7 7-7 7"></path>
            </svg>
          </a>
        </div>
      </div>
      <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
        <div class="w-16 h-16 inline-flex items-center justify-center rounded-full bg-indigo-100 mb-5 flex-shrink-0">
          <img src="/images/smoke.svg" alt="Cigarrillo"/>
        </div>
        <div class="flex-grow">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-3">Tóxicos</h2>
          <p class="leading-relaxed text-base">
            El consumo de sustancias tóxicas como el cigarrillo y el alcohol puede tener graves
            consecuencias para la salud física, mental y emocional.
          </p>
          <a href="/toxic" class="mt-3 text-indigo-500 inline-flex items-center">Aprende más
            <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-2" viewBox="0 0 24 24">
              <path d="M5 12h14M12 5l7 7-7 7"></path>
            </svg>
          </a>
        </div>
      </div>
    </div>
  </div>
</section>


<style lang="postcss">
.header-page {
  position: relative;
  background-color: rgba(6, 177, 43, 0.9); /* Colocamos un color verde con opacidad del 90% */
}

.header-page video {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  opacity: 0.6; /* Reducimos la opacidad del video para que el color de fondo sea visible */
}
</style>
