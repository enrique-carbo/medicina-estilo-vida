<svelte:head>
  <title>MEV - Estrés</title>
</svelte:head>

<!----------------------- Header ---------------------------------->

<section
  class="overflow-hidden bg-gray-50 sm:grid sm:grid-cols-2 sm:items-center"
>
  <div class="p-8 md:p-12 lg:px-16 lg:py-24">
    <div class="mx-auto max-w-xl text-center sm:text-left">
      <h2 class="text-2xl font-bold text-gray-900 md:text-3xl">
        ESTRÉS
      </h2>

      <p class="flex mt-4 text-gray-500 md:block">
        El estrés es una respuesta fisiológica y psicológica natural del cuerpo ante situaciones
        que se perciben como desafiantes o amenazantes. 
      </p>
      <p class="hidden text-gray-500 md:mt-4 md:block">
        El estrés puede ser causado por eventos estresantes externos, como una crisis financiera,
        un problema laboral o una situación de conflicto interpersonal, o por factores internos
        como preocupaciones y pensamientos negativos.
      </p>

    </div>
  </div>

  <img
    alt="Persona estresada"
    src="/images/stress.jpg"
    class="h-full w-full object-cover sm:h-[calc(100%_-_2rem)] sm:self-end sm:rounded-tl-[30px] md:h-[calc(100%_-_4rem)] md:rounded-tl-[60px]"
  />
</section>

<!----------------------------- Section 1 ---------------------------------------->

<section class="text-gray-600 body-font">
  <div class="container px-5 py-24 mx-auto">
    <div class="flex flex-wrap w-full mb-20 flex-col items-center text-center">
      <h1 class="sm:text-3xl text-2xl font-medium title-font mb-2 text-gray-900">
        Determinantes para el aumento del estrés en los individuos  
      </h1>
      <p class="lg:w-1/2 w-full leading-relaxed text-gray-500">
        Hay varios factores en el mundo moderno que contribuyen al aumento del estrés en las personas.  
      </p>
    </div>
    <div class="flex flex-wrap -m-4">
      <div class="xl:w-1/3 md:w-1/2 p-4">
        <div class="border border-gray-200 p-6 rounded-lg">
          <div class="w-16 h-16 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-4">
            <img src="/images/television.svg" alt="Television" />
          </div>
          <h2 class="text-lg text-gray-900 font-medium title-font mb-2">
            Sobrecarga de información
          </h2>
          <p class="leading-relaxed text-base">
            Vivimos en un mundo en el que estamos constantemente expuestos a una gran cantidad de
            información, a través de los medios de comunicación y las redes sociales, lo que puede
            ser abrumador y estresante.
          </p>
        </div>
      </div>
      <div class="xl:w-1/3 md:w-1/2 p-4">
        <div class="border border-gray-200 p-6 rounded-lg">
          <div class="w-16 h-16 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-4">
            <img src="/images/woman-tech.svg" alt="Mujer con computadora" />
          </div>
          <h2 class="text-lg text-gray-900 font-medium title-font mb-2">
            Tecnología  
          </h2>
          <p class="leading-relaxed text-base">
            El uso excesivo de la tecnología, como los teléfonos inteligentes y las computadoras,
            puede ser una fuente de estrés debido a la necesidad de estar siempre conectado y disponible.
          </p>
        </div>
      </div>
      <div class="xl:w-1/3 md:w-1/2 p-4">
        <div class="border border-gray-200 p-6 rounded-lg">
          <div class="w-16 h-16 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-4">
            <img src="/images/tools.svg" alt="Herramientas" />
          </div>
          <h2 class="text-lg text-gray-900 font-medium title-font mb-2">
            Presión laboral  
          </h2>
          <p class="leading-relaxed text-base">
            La presión laboral es otra fuente importante de estrés. Los trabajadores pueden enfrentarse
            a plazos ajustados, largas horas de trabajo, falta de autonomía y apoyo, y conflictos
            interpersonales.
          </p>
        </div>
      </div>
      <div class="xl:w-1/3 md:w-1/2 p-4">
        <div class="border border-gray-200 p-6 rounded-lg">
          <div class="w-16 h-16 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-4">
            <img src="/images/anxious-face.svg" alt="Emoticon ansioso"/>  
          </div>
          <h2 class="text-lg text-gray-900 font-medium title-font mb-2">
            Inseguridad laboral
          </h2>
          <p class="leading-relaxed text-base">
            La incertidumbre laboral, como la amenaza de despidos o la falta de estabilidad en el trabajo,
            puede generar ansiedad y estrés.
          </p>
        </div>
      </div>
      <div class="xl:w-1/3 md:w-1/2 p-4">
        <div class="border border-gray-200 p-6 rounded-lg">
          <div class="w-16 h-16 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-4">
            <img src="/images/money.svg" alt="Dinero" />
          </div>
          <h2 class="text-lg text-gray-900 font-medium title-font mb-2">
            Problemas financieros  
          </h2>
          <p class="leading-relaxed text-base">
            Las preocupaciones financieras, como la falta de ingresos o la deuda, también pueden ser una
            fuente de estrés en las personas.
          </p>
        </div>
      </div>
      <div class="xl:w-1/3 md:w-1/2 p-4">
        <div class="border border-gray-200 p-6 rounded-lg">
          <div class="w-16 h-16 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-4">
            <img src="/images/burguer.svg" alt="Hamburguesa" />
          </div>
          <h2 class="text-lg text-gray-900 font-medium title-font mb-2">
            Estilo de vida poco saludable
          </h2>
          <p class="leading-relaxed text-base">
            Un estilo de vida poco saludable, como una dieta pobre, falta de actividad física y malos
            hábitos de sueño, también pueden aumentar el estrés en las personas.
          </p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-------------------------- Section 2---------------------------->

<section class="text-gray-600 body-font bg-slate-100">
  <div class="container px-5 py-24 mx-auto">
    <div class="xl:w-1/2 lg:w-3/4 w-full mx-auto text-center">
      <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="inline-block w-8 h-8 text-gray-400 mb-8" viewBox="0 0 975.036 975.036">
        <path d="M925.036 57.197h-304c-27.6 0-50 22.4-50 50v304c0 27.601 22.4 50 50 50h145.5c-1.9 79.601-20.4 143.3-55.4 191.2-27.6 37.8-69.399 69.1-125.3 93.8-25.7 11.3-36.8 41.7-24.8 67.101l36 76c11.6 24.399 40.3 35.1 65.1 24.399 66.2-28.6 122.101-64.8 167.7-108.8 55.601-53.7 93.7-114.3 114.3-181.9 20.601-67.6 30.9-159.8 30.9-276.8v-239c0-27.599-22.401-50-50-50zM106.036 913.497c65.4-28.5 121-64.699 166.9-108.6 56.1-53.7 94.4-114.1 115-181.2 20.6-67.1 30.899-159.6 30.899-277.5v-239c0-27.6-22.399-50-50-50h-304c-27.6 0-50 22.4-50 50v304c0 27.601 22.4 50 50 50h145.5c-1.9 79.601-20.4 143.3-55.4 191.2-27.6 37.8-69.4 69.1-125.3 93.8-25.7 11.3-36.8 41.7-24.8 67.101l35.9 75.8c11.601 24.399 40.501 35.2 65.301 24.399z"></path>
      </svg>
      <p class="leading-relaxed text-xl">
        Sólo tengo tres cosas que enseñar: sencillez, paciencia, compasión. Estos tres son tus mayores tesoros.  
      </p>
      <span class="inline-block h-1 w-10 rounded bg-rose-500 mt-8 mb-6"></span>
      <h2 class="text-gray-900 font-medium title-font tracking-wider text-md">LAO TZU</h2>
      <p class="text-gray-500">Antiguo Filósofo Chino</p>
    </div>
  </div>
</section>

<!----------------------------- Section 3 ---------------------------------------------->

<section class="text-gray-600 body-font">
  <div class="text-center mt-20 mb-10">
    <h1 class="sm:text-3xl text-2xl font-medium title-font text-gray-900 mb-4">
      Estrategias para reducir o gestionar el estrés.
    </h1>
    <p class="text-base leading-relaxed xl:w-2/4 lg:w-3/4 mx-auto text-gray-500s">
      El estrés es un problema cada vez más común en nuestra sociedad y tiene graves consecuencias para
      la salud física y mental. Es por eso que es importante abordarlo adecuadamente para prevenir
      complicaciones.
    </p>
    <div class="flex mt-6 justify-center">
      <div class="w-16 h-1 rounded-full bg-emerald-500 inline-flex"></div>
    </div>
  </div>

  <div class="container px-5 py-10 mx-auto flex flex-wrap">
    <div class="lg:w-1/2 w-full mb-10 lg:mb-0 rounded-lg overflow-hidden">
      <img alt="Hombre meditando con los ojos cerrados" 
      class="object-cover object-center h-full w-full" 
      src="/images/man-meditate-sm.jpg">
    </div>
    <div class="flex flex-col flex-wrap lg:py-6 -mb-10 lg:w-1/2 lg:pl-12 lg:text-left text-center">
      <div class="flex flex-col mb-10 lg:items-start items-center">
        <div class="w-12 h-12 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-5">
          <img src="/images/meditation1.svg" alt="Mujer meditando" />
        </div>
        <div class="flex-grow">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-3">
            Meditación
          </h2>
          <p class="leading-relaxed text-base">
            Técnica de relajación que consiste en enfocar la mente en un objeto, pensamiento o
            actividad para lograr una sensación de calma y tranquilidad. La meditación puede ayudar
            a reducir la ansiedad y el estrés, mejorar la calidad del sueño y aumentar la sensación
            de bienestar.
          </p>
          
        </div>
      </div>
      <div class="flex flex-col mb-10 lg:items-start items-center">
        <div class="w-12 h-12 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-5">
          <img src="/images/lungs.svg" alt="Pulmones" />
        </div>
        <div class="flex-grow">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-3">
            Respiración profunda  
          </h2>
          <p class="leading-relaxed text-base">
            La respiración profunda es una técnica simple que se puede realizar en cualquier momento
            para reducir los niveles de estrés. La respiración profunda aumenta la variabilidad de la
            frecuencia cardíaca y reduce la ansiedad.
          </p>
          
        </div>
      </div>
      <div class="flex flex-col mb-10 lg:items-start items-center">
        <div class="w-12 h-12 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-5">
          <img src="/images/exercise-gym.svg" alt="Hombre levantando pesas"/>
        </div>
        <div class="flex-grow">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-3">
            Ejercicio físico
          </h2>
          <p class="leading-relaxed text-base">
            El ejercicio regular puede ayudar a reducir los niveles de estrés y mejorar el estado de ánimo.
            Se ha demostrado que el ejercicio cardiovascular y el entrenamiento de fuerza son especialmente
            eficaces.
          </p>
          
        </div>
      </div>
    </div>
  </div>
</section>

<!----------------------------- Section 4 ---------------------------------------------->

<section class="text-gray-600 body-font">
  <div class="container px-5 py-5 mx-auto flex flex-wrap">
    
    <div class="flex flex-col flex-wrap lg:py-6 -mb-10 lg:w-1/2 lg:pl-12 lg:text-left text-center">
      <div class="flex flex-col mb-10 lg:items-start items-center">
        <div class="w-12 h-12 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-5">
          <img src="/images/avatar-thinking.svg" alt="Mujer pensando"/>
        </div>
        <div class="flex-grow">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-3">
            Terapia cognitivo-conductual  
          </h2>
          <p class="leading-relaxed text-base">
            Esta forma de terapia se centra en cambiar los patrones de pensamiento negativos
            y en desarrollar habilidades para manejar situaciones estresantes.
          </p>
          
        </div>
      </div>
      <div class="flex flex-col mb-10 lg:items-start items-center">
        <div class="w-12 h-12 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-5">
          <img src="/images/yoga.svg" alt="Hombre haciendo yoga"/>
        </div>
        <div class="flex-grow">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-3">Yoga</h2>
          <p class="leading-relaxed text-base">
            El yoga combina la práctica de posturas, la respiración y la meditación para promover la
            relajación y reducir el estrés. Estudios han demostrado que la práctica regular de yoga
            puede reducir los niveles de cortisol y mejorar la calidad del sueño.
          </p>
          
        </div>
      </div>
      <div class="flex flex-col mb-10 lg:items-start items-center">
        <div class="w-12 h-12 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-5">
          <img src="/images/playlist.svg" alt="Clave musical y corazon"/>
        </div>
        <div class="flex-grow">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-3">Otras</h2>
          <p class="leading-relaxed text-base">
            Existen otras estrategias que pueden ser de utilidad como: terapias de arte, con música,
            de risas, de socialización que pueden aportar beneficios, solas o combinadas.
          </p>
          
        </div>
      </div>
    </div>

    <div class="lg:w-1/2 w-full my-10 lg:my-0 rounded-lg overflow-hidden">
      <img alt="Gente haciendo yoga en el parque" class="object-cover object-center h-full w-full" 
      src="/images/yoga-sm.jpg">
    </div>

  </div>
</section>