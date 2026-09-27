# Frank
Frank - HR Partner
echo "# Frank" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/sofiasauretti-ai/Frank.git
git push -u origin main
<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Frank — Gestión de Personas para Empresas en Crecimiento</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <style>
    body { font-family: 'Inter', sans-serif; }
    .bg-gradient-hero { background: radial-gradient(circle at top right, #eef2ff 0%, #f8fafc 50%, #ffffff 100%); }
    .accordion-content { max-height: 0; overflow: hidden; transition: max-height 0.3s ease-out; }
    .accordion-content.open { max-height: 1000px; }
  </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased selection:bg-indigo-500 selection:text-white">

  <!-- NAVBAR -->
  <nav class="sticky top-0 z-50 bg-slate-50/80 backdrop-blur-md border-b border-slate-100">
    <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
      <div class="flex items-center gap-2">
        <div class="grid grid-cols-2 gap-0.5 w-6 h-6 bg-indigo-600 p-1 rounded-md">
          <div class="bg-white rounded-sm"></div>
          <div class="bg-indigo-300 rounded-sm"></div>
          <div class="bg-indigo-300 rounded-sm"></div>
          <div class="bg-white rounded-sm"></div>
        </div>
        <span class="font-bold text-xl text-slate-900">Frank</span>
      </div>
      <div class="hidden md:flex items-center gap-8 text-sm font-medium text-slate-600">
        <a href="#que-hacemos" class="hover:text-indigo-600 transition">Qué hacemos</a>
        <a href="#planes" class="hover:text-indigo-600 transition">Planes</a>
        <a href="#recruiting" class="hover:text-indigo-600 transition">Recruiting</a>
      </div>
      <a href="#contacto" class="bg-indigo-600 hover:bg-indigo-700 text-white font-medium text-sm px-5 py-2.5 rounded-full transition shadow-sm">
        Hablemos
      </a>
    </div>
  </nav>

  <!-- HERO SECTION -->
  <section class="bg-gradient-hero pt-12 pb-20 px-6">
    <div class="max-w-4xl mx-auto">
      <span class="inline-block bg-indigo-50 text-indigo-600 text-xs font-bold tracking-widest px-3 py-1 rounded-full uppercase mb-6 border border-indigo-100">
        FRANK
      </span>
      <h1 class="text-4xl md:text-6xl font-extrabold text-slate-900 leading-tight mb-6">
        Hacer crecer tu equipo no debería significar hacer crecer tu lista de pendientes.
      </h1>
      <p class="text-lg md:text-xl text-slate-500 mb-8 max-w-2xl">
        Te ayudamos a construir todo lo que tu empresa necesita a medida que crece.
      </p>
      <a href="#contacto" class="inline-flex items-center gap-2 bg-indigo-600 hover:bg-indigo-700 text-white font-medium px-6 py-3.5 rounded-2xl shadow-lg shadow-indigo-200 transition">
        Hablemos <span>→</span>
      </a>

      <!-- HERO VISUAL INDICATOR -->
      <div class="mt-16 bg-white rounded-3xl p-6 shadow-xl border border-slate-100 space-y-4 max-w-2xl mx-auto">
        <div class="flex justify-between items-center p-3 hover:bg-slate-50 rounded-xl transition">
          <span class="font-medium text-slate-700">Personas</span>
          <div class="flex gap-1.5"><span class="w-2.5 h-2.5 rounded-full bg-cyan-400"></span><span class="w-2.5 h-2.5 rounded-full bg-slate-200"></span><span class="w-2.5 h-2.5 rounded-full bg-slate-200"></span></div>
        </div>
        <div class="flex justify-between items-center p-3 hover:bg-slate-50 rounded-xl transition">
          <span class="font-medium text-slate-700">Procesos</span>
          <div class="flex gap-1.5"><span class="w-2.5 h-2.5 rounded-full bg-indigo-500"></span><span class="w-2.5 h-2.5 rounded-full bg-cyan-400"></span><span class="w-2.5 h-2.5 rounded-full bg-slate-200"></span></div>
        </div>
        <div class="flex justify-between items-center p-3 hover:bg-slate-50 rounded-xl transition">
          <span class="font-medium text-slate-700">Supervisores</span>
          <div class="flex gap-1.5"><span class="w-2.5 h-2.5 rounded-full bg-indigo-500"></span><span class="w-2.5 h-2.5 rounded-full bg-indigo-500"></span><span class="w-2.5 h-2.5 rounded-full bg-cyan-400"></span></div>
        </div>
      </div>
    </div>
  </section>

  <!-- SECCIÓN CRECIMIENTO -->
  <section id="que-hacemos" class="py-20 px-6 max-w-6xl mx-auto">
    <div class="bg-white rounded-3xl p-8 md:p-12 border border-slate-100 shadow-sm grid md:grid-cols-2 gap-12 items-center">
      <div>
        <span class="text-xs font-bold text-indigo-600 tracking-wider uppercase">CRECIMIENTO</span>
        <h2 class="text-3xl md:text-4xl font-bold text-slate-900 mt-2 mb-4 leading-tight">
          Vos hacés crecer el negocio. Nosotros nos ocupamos de las personas.
        </h2>
        <p class="text-slate-700 font-medium mb-3">Una extensión de tu equipo, para lo que necesites.</p>
        <p class="text-slate-500 text-sm leading-relaxed">
          Desde gestionar tu área de RRHH hasta acompañarte en las decisiones del día a día, estamos para ayudarte a que vos puedas enfocarte en hacer crecer tu negocio.
        </p>
      </div>

      <div class="grid grid-cols-2 gap-4">
        <div class="bg-slate-50 p-5 rounded-2xl border border-slate-100">
          <span class="text-indigo-600 font-bold text-lg">01</span>
          <p class="font-semibold text-slate-800 text-sm mt-1">Lo operativo, resuelto</p>
        </div>
        <div class="bg-slate-50 p-5 rounded-2xl border border-slate-100">
          <span class="text-indigo-600 font-bold text-lg">02</span>
          <p class="font-semibold text-slate-800 text-sm mt-1">Procesos que sostienen</p>
        </div>
        <div class="bg-slate-50 p-5 rounded-2xl border border-slate-100">
          <span class="text-indigo-600 font-bold text-lg">03</span>
          <p class="font-semibold text-slate-800 text-sm mt-1">Líderes acompañados</p>
        </div>
        <div class="bg-slate-50 p-5 rounded-2xl border border-slate-100">
          <span class="text-indigo-600 font-bold text-lg">04</span>
          <p class="font-semibold text-slate-800 text-sm mt-1">Una función de People</p>
        </div>
      </div>
    </div>
  </section>

  <!-- SECCIÓN INFRAESTRUCTURA -->
  <section class="py-12 px-6 max-w-6xl mx-auto">
    <div class="bg-white rounded-3xl p-8 md:p-12 border border-slate-100 shadow-sm space-y-10">
      <h2 class="text-3xl md:text-4xl font-bold text-slate-900 max-w-2xl leading-tight">
        Construimos la infraestructura que permite que tu equipo crezca con vos.
      </h2>
      <div class="grid md:grid-cols-2 gap-6">
        <div class="bg-slate-50 p-6 rounded-2xl border border-slate-100">
          <span class="text-xs font-bold text-cyan-500 bg-cyan-50 px-2.5 py-1 rounded-md">01</span>
          <h3 class="font-bold text-slate-900 mt-3 mb-1">Más autonomía</h3>
          <p class="text-slate-500 text-sm leading-relaxed">Procesos y herramientas para que el equipo pueda avanzar sin que todo dependa de una persona.</p>
        </div>
        <div class="bg-slate-50 p-6 rounded-2xl border border-slate-100">
          <span class="text-xs font-bold text-cyan-500 bg-cyan-50 px-2.5 py-1 rounded-md">02</span>
          <h3 class="font-bold text-slate-900 mt-3 mb-1">Una mejor experiencia</h3>
          <p class="text-slate-500 text-sm leading-relaxed">Inducción, procesos y formas de trabajar que hacen más fácil ser parte de la empresa.</p>
        </div>
        <div class="bg-slate-50 p-6 rounded-2xl border border-slate-100">
          <span class="text-xs font-bold text-indigo-500 bg-indigo-50 px-2.5 py-1 rounded-md">03</span>
          <h3 class="font-bold text-slate-900 mt-3 mb-1">Líderes con herramientas</h3>
          <p class="text-slate-500 text-sm leading-relaxed">Acompañamiento para que quienes lideran equipos puedan gestionar mejor.</p>
        </div>
        <div class="bg-slate-50 p-6 rounded-2xl border border-slate-100">
          <span class="text-xs font-bold text-indigo-500 bg-indigo-50 px-2.5 py-1 rounded-md">04</span>
          <h3 class="font-bold text-slate-900 mt-3 mb-1">Una cultura que escala</h3>
          <p class="text-slate-500 text-sm leading-relaxed">Convertimos lo que hace especial a la empresa en formas de trabajar que el equipo pueda vivir y transmitir.</p>
        </div>
      </div>
      <p class="text-center font-bold text-slate-800 text-lg pt-4">
        Más estructura para tu equipo. Más espacio para vos.
      </p>
    </div>
  </section>

  <!-- PLANES Y TARJETAS -->
  <section id="planes" class="py-20 px-6 max-w-6xl mx-auto">
    <div class="text-center max-w-2xl mx-auto mb-12">
      <h2 class="text-3xl md:text-4xl font-bold text-slate-900 mb-3">Una solución para cada etapa</h2>
      <p class="text-slate-500 text-sm">Desde resolver lo operativo hasta construir una función completa de gestión de personas.</p>
    </div>

    <div class="grid lg:grid-cols-3 gap-8 items-start">
      <!-- CARD 1: ESENCIAL -->
      <div class="bg-white rounded-3xl p-8 border border-slate-200 shadow-sm flex flex-col justify-between min-h-[520px]">
        <div>
          <span class="text-xs font-bold text-slate-400 tracking-wider uppercase">ESENCIAL</span>
          <h3 class="text-xl font-bold text-slate-900 mt-2 mb-3">Que lo operativo deje de depender de vos.</h3>
          <p class="text-xs text-slate-500 mb-6 leading-relaxed">Para empresas que empiezan a sentir el peso de gestionar un equipo cada vez más grande, pero todavía no necesitan una función completa de People.</p>
          
          <ul class="space-y-2 text-xs text-slate-700 font-medium mb-4">
            <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-indigo-600"></span>Diagnóstico inicial del área de RRHH</li>
            <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-indigo-600"></span>Altas, bajas y modificaciones</li>
            <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-indigo-600"></span>Legajos y documentación</li>
            <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-indigo-600"></span>Vacaciones, licencias y ausencias</li>
          </ul>

          <div id="extra-plan-1" class="accordion-content">
            <ul class="space-y-2 text-xs text-slate-700 font-medium pt-2 border-t border-slate-100">
              <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-indigo-600"></span>Coordinación de liquidación de sueldos</li>
              <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-indigo-600"></span>Canal de consultas de personas</li>
              <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-indigo-600"></span>Seguimiento semanal con founders</li>
            </ul>
          </div>
          <button onclick="toggleAccordion('extra-plan-1', this)" class="text-xs font-bold text-indigo-600 hover:text-indigo-800 transition mt-2">
            Ver qué incluye +
          </button>
        </div>

        <div class="pt-8 border-t border-slate-100 mt-6">
          <p class="text-sm font-semibold text-slate-900 mb-4">Desde <span class="text-lg font-extrabold text-indigo-600">USD 12</span> por empleado <span class="text-xs font-normal text-slate-400">/ mes</span></p>
          <a href="#contacto" class="block w-full text-center bg-indigo-600 hover:bg-indigo-700 text-white font-medium text-sm py-3 rounded-xl transition">
            Me interesa este plan
          </a>
        </div>
      </div>

      <!-- CARD 2: INFRAESTRUCTURA (DESTACADA) -->
      <div class="bg-slate-800 text-white rounded-3xl p-8 border border-slate-700 shadow-xl flex flex-col justify-between min-h-[520px] relative">
        <div>
          <span class="text-xs font-bold text-cyan-400 tracking-wider uppercase">INFRAESTRUCTURA</span>
          <h3 class="text-xl font-bold mt-2 mb-3">Que tu empresa tenga procesos que acompañen su crecimiento.</h3>
          <p class="text-xs text-slate-300 mb-6 leading-relaxed">Para equipos que necesitan construir una forma de trabajar que acompañe una empresa más grande.</p>
          
          <ul class="space-y-2 text-xs text-slate-200 font-medium mb-4">
            <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-cyan-400"></span>Diagnóstico organizacional</li>
            <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-cyan-400"></span>Roles y responsabilidades</li>
            <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-cyan-400"></span>Descripciones de puestos y perfiles</li>
            <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-cyan-400"></span>Niveles y bandas salariales</li>
          </ul>

          <div id="extra-plan-2" class="accordion-content">
            <ul class="space-y-2 text-xs text-slate-200 font-medium pt-2 border-t border-slate-700">
              <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-cyan-400"></span>Diseño de proceso de onboarding</li>
              <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-cyan-400"></span>Políticas de People y manuales</li>
              <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-cyan-400"></span>Herramientas para líderes</li>
              <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-cyan-400"></span>Coordinación entre equipos</li>
            </ul>
          </div>
          <button onclick="toggleAccordion('extra-plan-2', this)" class="text-xs font-bold text-cyan-400 hover:text-cyan-300 transition mt-2">
            Ver qué incluye +
          </button>
        </div>

        <div class="pt-8 border-t border-slate-700 mt-6">
          <p class="text-sm font-semibold mb-4">Desde <span class="text-lg font-extrabold text-cyan-400">USD 22</span> por empleado <span class="text-xs font-normal text-slate-400">/ mes</span></p>
          <a href="#contacto" class="block w-full text-center bg-cyan-400 hover:bg-cyan-300 text-slate-900 font-bold text-sm py-3 rounded-xl transition">
            Quiero construir mi infraestructura
          </a>
        </div>
      </div>

      <!-- CARD 3: FRACTIONAL HR -->
      <div class="bg-white rounded-3xl p-8 border border-slate-200 shadow-sm flex flex-col justify-between min-h-[520px]">
        <div>
          <span class="text-xs font-bold text-slate-400 tracking-wider uppercase">FRACTIONAL HR</span>
          <h3 class="text-xl font-bold text-slate-900 mt-2 mb-3">Una función de People operando con vos.</h3>
          <p class="text-xs text-slate-500 mb-4 leading-relaxed">Para empresas que ya necesitan una función de RRHH activa y recurrente, sin construir todavía un equipo interno completo.</p>
          
          <div class="bg-indigo-50/70 p-3 rounded-xl mb-4 border border-indigo-100">
            <p class="text-xs font-semibold text-indigo-900 mb-1">Una extensión de tu equipo.</p>
            <p class="text-[11px] text-indigo-700 leading-tight">Trabajamos dentro de tu operación, entendiendo cómo funciona tu empresa y construyendo desde ahí.</p>
          </div>

          <ul class="space-y-2 text-xs text-slate-700 font-medium mb-4">
            <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-indigo-600"></span>Referente de Personas integrado al negocio</li>
            <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-indigo-600"></span>Acompañamiento a founders y líderes</li>
            <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-indigo-600"></span>Roadmap de RRHH y Desempeño</li>
          </ul>

          <div id="extra-plan-3" class="accordion-content">
            <ul class="space-y-2 text-xs text-slate-700 font-medium pt-2 border-t border-slate-100">
              <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-indigo-600"></span>Desarrollo de liderazgo y carrera</li>
              <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-indigo-600"></span>Workforce planning y Métricas</li>
              <li class="flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-indigo-600"></span>Clima, retención y situaciones complejas</li>
            </ul>
          </div>
          <button onclick="toggleAccordion('extra-plan-3', this)" class="text-xs font-bold text-indigo-600 hover:text-indigo-800 transition mt-2">
            Ver qué incluye +
          </button>
        </div>

        <div class="pt-8 border-t border-slate-100 mt-6">
          <p class="text-sm font-semibold text-slate-900 mb-4">Desde <span class="text-lg font-extrabold text-indigo-600">USD 40</span> por empleado <span class="text-xs font-normal text-slate-400">/ mes</span></p>
          <a href="#contacto" class="block w-full text-center bg-indigo-600 hover:bg-indigo-700 text-white font-medium text-sm py-3 rounded-xl transition">
            Quiero evaluar Fractional HR
          </a>
        </div>
      </div>
    </div>
    <p class="text-center text-xs text-slate-400 mt-6">Definimos el alcance y el valor final junto con vos.</p>
  </section>

  <!-- CALCULADORA DE TIEMPO INTERACTIVA -->
  <section class="py-16 px-6 max-w-4xl mx-auto">
    <div class="bg-white rounded-3xl p-8 md:p-12 border border-slate-200 shadow-xl space-y-8">
      <h2 class="text-3xl font-extrabold text-slate-900 leading-tight">
        ¿Cuánto tiempo te lleva hacer crecer tu equipo?
      </h2>

      <!-- PARAMETROS CALCULADORA -->
      <div class="grid md:grid-cols-2 gap-6">
        <div>
          <label class="block text-xs font-semibold text-slate-700 mb-2">¿Cuántas personas incorporás por año?</label>
          <div class="flex items-center gap-3">
            <input type="number" id="calc-personas" value="6" min="1" oninput="calcularTiempo()" class="w-full bg-slate-50 border border-slate-200 p-3 rounded-xl text-sm font-semibold text-slate-800 focus:outline-none focus:border-indigo-500">
            <span class="text-xs font-medium text-slate-400 w-20">personas</span>
          </div>
        </div>

        <div>
          <label class="block text-xs font-semibold text-slate-700 mb-2">¿Cuánto tiempo te lleva incorporar a alguien?</label>
          <div class="flex items-center gap-3">
            <input type="number" id="calc-dias-busqueda" value="2.5" step="0.5" min="0" oninput="calcularTiempo()" class="w-full bg-slate-50 border border-slate-200 p-3 rounded-xl text-sm font-semibold text-slate-800 focus:outline-none focus:border-indigo-500">
            <span class="text-xs font-medium text-slate-400 w-20">días</span>
          </div>
        </div>

        <div>
          <label class="block text-xs font-semibold text-slate-700 mb-2">¿Cuánto tiempo pasa hasta que trabaja de manera autónoma?</label>
          <div class="flex items-center gap-3">
            <input type="number" id="calc-semanas-onboarding" value="8" min="0" oninput="calcularTiempo()" class="w-full bg-slate-50 border border-slate-200 p-3 rounded-xl text-sm font-semibold text-slate-800 focus:outline-none focus:border-indigo-500">
            <span class="text-xs font-medium text-slate-400 w-20">semanas</span>
          </div>
        </div>

        <div>
          <label class="block text-xs font-semibold text-slate-700 mb-2">¿Cuántas horas por semana invertís vos y tu equipo en gestionar personas?</label>
          <div class="flex items-center gap-3">
            <input type="number" id="calc-horas-gestion" value="6" min="0" oninput="calcularTiempo()" class="w-full bg-slate-50 border border-slate-200 p-3 rounded-xl text-sm font-semibold text-slate-800 focus:outline-none focus:border-indigo-500">
            <span class="text-xs font-medium text-slate-400 w-20">horas</span>
          </div>
        </div>
      </div>

      <!-- RESULTADO AUTOMÁTICO DE LA CALCULADORA -->
      <div class="bg-indigo-50/50 p-6 rounded-2xl border border-indigo-100/80 space-y-4">
        <p class="text-xs font-bold text-slate-400 uppercase tracking-wider">Tiempo que tu equipo dedica hoy a People, por año</p>
        <div class="flex flex-wrap items-baseline gap-3">
          <span id="calc-total-horas" class="text-4xl md:text-5xl font-extrabold text-indigo-600">408 horas</span>
          <span class="text-2xl md:text-3xl font-extrabold text-cyan-500">→ <span id="calc-total-dias">51</span> días de trabajo</span>
        </div>
        <p id="calc-explicacion" class="text-xs text-slate-500 leading-relaxed">
          Calculado con los datos que ingresaste: 6 incorporaciones × 2.5 días de 8 horas, más 8 semanas × 6 horas semanales de acompañamiento por incorporación.
        </p>
        <div class="pt-2">
          <a href="#contacto" class="inline-block bg-indigo-600 hover:bg-indigo-700 text-white font-medium text-xs px-6 py-3 rounded-xl transition">
            Hablemos
          </a>
        </div>
      </div>

      <p class="text-center font-bold text-slate-800 text-sm">
        Más capacidad para gestionar tu equipo. Más capacidad para hacer crecer el negocio.
      </p>
    </div>
  </section>

  <!-- SECCIÓN RECRUITING -->
  <section id="recruiting" class="py-16 px-6 max-w-6xl mx-auto">
    <div class="bg-white rounded-3xl p-8 md:p-12 border border-slate-100 shadow-sm space-y-8">
      <div>
        <span class="text-xs font-bold text-indigo-600 tracking-wider uppercase">RECRUITING</span>
        <h2 class="text-3xl md:text-4xl font-bold text-slate-900 mt-2 mb-3">
          Y cuando lo que necesitás es sumar a alguien.
        </h2>
        <p class="text-slate-600 font-medium text-sm">También podemos ayudarte a encontrarlo.</p>
        <p class="text-slate-400 text-xs mt-1">Primero entendemos qué necesitás. Después nos encargamos de la búsqueda.</p>
      </div>

      <!-- PASOS PROCESO RECRUITING -->
      <div class="grid grid-cols-2 md:grid-cols-5 gap-3">
        <div class="bg-slate-50 p-4 rounded-xl border border-slate-100">
          <span class="text-cyan-500 font-bold text-xs">01</span>
          <p class="font-semibold text-slate-800 text-xs mt-1">Definición del rol</p>
        </div>
        <div class="bg-slate-50 p-4 rounded-xl border border-slate-100">
          <span class="text-cyan-500 font-bold text-xs">02</span>
          <p class="font-semibold text-slate-800 text-xs mt-1">Búsqueda</p>
        </div>
        <div class="bg-slate-50 p-4 rounded-xl border border-slate-100">
          <span class="text-cyan-500 font-bold text-xs">03</span>
          <p class="font-semibold text-slate-800 text-xs mt-1">Entrevistas</p>
        </div>
        <div class="bg-slate-50 p-4 rounded-xl border border-slate-100">
          <span class="text-cyan-500 font-bold text-xs">04</span>
          <p class="font-semibold text-slate-800 text-xs mt-1">Selección</p>
        </div>
        <div class="bg-slate-50 p-4 rounded-xl border border-slate-100 col-span-2 md:col-span-1">
          <span class="text-cyan-500 font-bold text-xs">05</span>
          <p class="font-semibold text-slate-800 text-xs mt-1">Ingreso</p>
        </div>
      </div>

      <!-- PRECIOS RECRUITING -->
      <div class="grid md:grid-cols-3 gap-4">
        <div class="bg-slate-50 p-5 rounded-2xl border border-slate-100">
          <p class="font-semibold text-slate-800 text-xs mb-1">Operativos y Administrativos</p>
          <p class="text-indigo-600 font-bold text-sm">desde <span class="text-lg">40%</span> de un sueldo bruto</p>
        </div>
        <div class="bg-slate-50 p-5 rounded-2xl border border-slate-100">
          <p class="font-semibold text-slate-800 text-xs mb-1">Roles profesionales y especialistas</p>
          <p class="text-indigo-600 font-bold text-sm">desde <span class="text-lg">50%</span> de un sueldo bruto</p>
        </div>
        <div class="bg-slate-50 p-5 rounded-2xl border border-slate-100">
          <p class="font-semibold text-slate-800 text-xs mb-1">Perfiles de tecnología</p>
          <p class="text-indigo-600 font-bold text-sm">desde <span class="text-lg">70%</span> de un sueldo bruto</p>
        </div>
      </div>

      <div class="flex flex-col md:flex-row items-center gap-6 pt-2">
        <a href="#contacto" class="w-full md:w-auto bg-indigo-600 hover:bg-indigo-700 text-white font-medium text-sm px-6 py-3.5 rounded-2xl transition text-center shrink-0">
          Necesito contratar
        </a>
        <p class="text-[11px] text-slate-400 leading-normal">
          Porcentaje mínimo sobre el salario mensual bruto. El precio nunca supera el equivalente a un salario mensual bruto. Búsquedas ejecutivas o de alta complejidad se cotizan según el perfil y el mercado.
        </p>
      </div>
    </div>
  </section>

  <!-- FORMULARIO DE VALIDACIÓN PROYECTO TESIS -->
  <section class="py-12 px-6 max-w-4xl mx-auto">
    <div class="bg-cyan-50/40 border border-cyan-100 rounded-3xl p-8 md:p-10 space-y-6">
      <span class="text-[10px] font-bold text-cyan-600 tracking-wider uppercase bg-cyan-100/60 px-2.5 py-1 rounded-md">VALIDACIÓN</span>
      <h2 class="text-2xl md:text-3xl font-bold text-slate-900">Ayudanos a validar Frank</h2>
      <p class="text-xs text-slate-600 leading-relaxed max-w-2xl">
        Frank es nuestro proyecto de tesis de maestría. Está diseñado para ser tu aliado en la gestión de personas: te da acceso a las herramientas, servicios y especialistas que necesitás para llevar a cabo funciones de RRHH, profesionalizarlo o ampliar capacidad. Así, founders y equipos pueden enfocarse en hacer crecer el negocio.
      </p>

      <form id="form-validacion" class="space-y-4 max-w-md" onsubmit="event.preventDefault(); alert('¡Gracias por tus respuestas de validación!');">
        <div>
          <label class="block text-xs font-semibold text-slate-700 mb-1">Tu email</label>
          <input type="email" placeholder="nombre@empresa.com" required class="w-full bg-white border border-slate-200 p-3 rounded-xl text-xs text-slate-800 focus:outline-none focus:border-indigo-500">
          <span class="text-[10px] text-slate-400 mt-1 block">Lo usamos únicamente para evitar respuestas duplicadas.</span>
        </div>

        <div>
          <label class="block text-xs font-semibold text-slate-700 mb-2">¿Considerarías sumar Frank a tu organización?</label>
          <div class="flex gap-4">
            <label class="flex items-center gap-2 bg-white px-4 py-2.5 rounded-xl border border-slate-200 text-xs font-medium text-slate-700 cursor-pointer hover:bg-slate-50">
              <input type="radio" name="validar" value="si" class="text-indigo-600"> Sí
            </label>
            <label class="flex items-center gap-2 bg-white px-4 py-2.5 rounded-xl border border-slate-200 text-xs font-medium text-slate-700 cursor-pointer hover:bg-slate-50">
              <input type="radio" name="validar" value="no" class="text-indigo-600"> No
            </label>
          </div>
        </div>

        <button type="submit" class="bg-indigo-400 hover:bg-indigo-500 text-white font-semibold text-xs px-6 py-3 rounded-xl transition">
          Enviar respuestas
        </button>
      </form>
    </div>
  </section>

  <!-- FORMULARIO DE CONTACTO PRINCIPAL -->
  <section id="contacto" class="py-20 px-6 max-w-5xl mx-auto">
    <div class="bg-slate-800 text-white rounded-3xl p-8 md:p-12 shadow-2xl grid md:grid-cols-2 gap-10 items-center border border-slate-700">
      <div>
        <h2 class="text-3xl md:text-4xl font-bold mb-4 leading-tight">
          Vos hacés crecer el negocio. Nosotros nos ocupamos de las personas.
        </h2>
        <p class="text-slate-300 text-sm leading-relaxed">
          Desde gestionar tu área de RRHH hasta acompañarte en las decisiones del día a día, estamos para ayudarte a que vos puedas enfocarte en hacer crecer tu negocio.
        </p>
      </div>

      <form id="form-contacto" class="space-y-4" onsubmit="event.preventDefault(); alert('¡Gracias por comunicarte! Te contactaremos a la brevedad.');">
        <div class="grid grid-cols-2 gap-3">
          <input type="text" placeholder="Nombre" required class="w-full bg-slate-700/60 p-3.5 rounded-xl border border-slate-600 text-xs text-white placeholder-slate-400 focus:outline-none focus:border-cyan-400">
          <input type="text" placeholder="Empresa" required class="w-full bg-slate-700/60 p-3.5 rounded-xl border border-slate-600 text-xs text-white placeholder-slate-400 focus:outline-none focus:border-cyan-400">
        </div>
        <div class="grid grid-cols-2 gap-3">
          <input type="email" placeholder="Email" required class="w-full bg-slate-700/60 p-3.5 rounded-xl border border-slate-600 text-xs text-white placeholder-slate-400 focus:outline-none focus:border-cyan-400">
          <input type="text" placeholder="Cantidad de personas" required class="w-full bg-slate-700/60 p-3.5 rounded-xl border border-slate-600 text-xs text-white placeholder-slate-400 focus:outline-none focus:border-cyan-400">
        </div>
        <select class="w-full bg-slate-700/60 p-3.5 rounded-xl border border-slate-600 text-xs text-slate-300 focus:outline-none focus:border-cyan-400">
          <option value="">¿Qué necesitás de People?</option>
          <option value="esencial">Esencial</option>
          <option value="infraestructura">Infraestructura</option>
          <option value="fractional">Fractional HR</option>
          <option value="recruiting">Recruiting</option>
        </select>
        <textarea placeholder="Mensaje" rows="3" class="w-full bg-slate-700/60 p-3.5 rounded-xl border border-slate-600 text-xs text-white placeholder-slate-400 focus:outline-none focus:border-cyan-400"></textarea>
        <button type="submit" class="w-full bg-cyan-400 hover:bg-cyan-300 text-slate-900 font-bold text-xs p-3.5 rounded-xl transition shadow-lg">
          Hablemos
        </button>
      </form>
    </div>
  </section>

  <!-- LÓGICA JAVASCRIPT -->
  <script>
    // 1. LÓGICA DE DESPLEGABLES (ACCORDION DE PLANES)
    function toggleAccordion(id, btn) {
      const content = document.getElementById(id);
      if (content.classList.contains('open')) {
        content.classList.remove('open');
        btn.innerText = "Ver qué incluye +";
      } else {
        content.classList.add('open');
        btn.innerText = "Ver menos -";
      }
    }

    // 2. LÓGICA CALCULADORA MATEMÁTICA EN TIEMPO REAL
    function calcularTiempo() {
      const personas = parseFloat(document.getElementById('calc-personas').value) || 0;
      const diasBusqueda = parseFloat(document.getElementById('calc-dias-busqueda').value) || 0;
      const semanasOnboarding = parseFloat(document.getElementById('calc-semanas-onboarding').value) || 0;
      const horasGestion = parseFloat(document.getElementById('calc-horas-gestion').value) || 0;

      // Fórmula matemática:
      // Horas búsqueda = Personas * Días Búsqueda * 8 hrs laborales
      // Horas gestión onboarding = Personas * Semanas * Horas de gestión semanales
      const horasBusquedaTotal = personas * diasBusqueda * 8;
      const horasGestionTotal = personas * semanasOnboarding * horasGestion;
      const horasTotales = Math.round(horasBusquedaTotal + horasGestionTotal);
      
      // Días laborales (jornadas de 8 horas)
      const diasTotales = Math.round(horasTotales / 8);

      // Actualizar interfaz
      document.getElementById('calc-total-horas').innerText = `${horasTotales} horas`;
      document.getElementById('calc-total-dias').innerText = diasTotales;
      document.getElementById('calc-explicacion').innerText = 
        `Calculado con los datos que ingresaste: ${personas} incorporaciones × ${diasBusqueda} días de 8 horas, más ${semanasOnboarding} semanas × ${horasGestion} horas semanales de acompañamiento por incorporación.`;
    }

    // Ejecutar cálculo inicial al cargar
    window.onload = function() {
      calcularTiempo();
    };
  </script>
</body>
</html>
