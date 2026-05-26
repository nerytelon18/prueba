<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>examenA_25000701 - Logística y Cadenas de Suministro</title>
    
    <!-- Tailwind CSS para Responsive Design rápido -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Enlace al archivo de Manifiesto físico para la PWA -->
    <link rel="manifest" href="manifest.json">

    <style>
        /* Paletas de Colores Pastel en Variables CSS */
        :root {
            --bg-color: #f0f4f8;         /* Fondo azul-grisáceo muy suave */
            --text-color: #2c3e50;       /* Texto gris oscuro suave */
            --card-bg: #ffffff;          /* Tarjetas blanco puro */
            --border-color: #e2e8f0;     /* Bordes pastel tenues */
            --primary: #a5b4fc;          /* Violeta pastel */
            --primary-hover: #c7d2fe;    /* Violeta pastel claro */
            --secondary: #93c5fd;        /* Celeste pastel */
            --secondary-hover: #bfdbfe;  /* Celeste pastel claro */
            --accent: #fbcfe8;           /* Rosa pastel */
            --accent-dark: #f472b6;      /* Rosa pastel más fuerte */
            --btn-text: #2c3e50;         /* Texto para botones en modo claro */
            --welcome-text: #eab308;     /* Amarillo pastel legible para el modo claro */
        }

        body.dark {
            --bg-color: #0f172a;         /* Azul noche profundo */
            --text-color: #f1f5f9;       /* Texto crema muy claro */
            --card-bg: #1e293b;          /* Tarjetas gris azulado oscuro */
            --border-color: #334155;     /* Bordes oscuros suaves */
            --primary: #818cf8;          /* Índigo pastel vibrante */
            --primary-hover: #4f46e5;    
            --secondary: #38bdf8;        /* Cyan pastel vibrante */
            --secondary-hover: #0284c7;  
            --accent: #f472b6;           
            --accent-dark: #ec4899;
            --btn-text: #ffffff;         /* Texto para botones en modo oscuro */
            --welcome-text: #ffffff;     /* Blanco puro en modo oscuro */
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            transition: background-color 0.4s cubic-bezier(0.4, 0, 0.2, 1), color 0.4s cubic-bezier(0.4, 0, 0.2, 1);
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            overflow-x: hidden;
        }

        /* Contenedores con estética pastel */
        .contenedor-seccion {
            background-color: var(--card-bg);
            border: 2px solid var(--border-color);
            border-radius: 1.25rem;
            transition: background-color 0.4s ease, border-color 0.4s ease;
        }

        /* Botones y Enlaces Interactivos */
        .enlace-interactivo {
            display: inline-flex;
            align-items: center;
            padding: 0.75rem 1.5rem;
            border-radius: 9999px;
            font-weight: 600;
            text-decoration: none;
            color: var(--btn-text);
            background: var(--primary);
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }

        .enlace-interactivo:hover {
            transform: translateY(-2px) scale(1.03);
            background: var(--primary-hover);
        }

        /* Estilo para los botones secundarios */
        .btn-secundario {
            background-color: var(--secondary);
            color: var(--btn-text);
        }

        .btn-secundario:hover {
            background-color: var(--secondary-hover);
        }

        /* Modal personalizado */
        #customModal, #confirmModal {
            background: rgba(15, 23, 42, 0.6);
            backdrop-filter: blur(4px);
        }

        /* Animaciones para cambio de pantallas */
        .tab-content {
            display: none;
            animation: fadeIn 0.3s ease-in-out forwards;
        }

        .tab-content.active {
            display: block;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body class="min-h-screen flex flex-col justify-between">

    <!-- Header adaptable (clásico arriba en PC, compacto en móvil) -->
    <header class="py-4 px-4 md:px-8 shadow-md flex justify-between items-center sticky top-0 z-40 border-b border-opacity-10 border-slate-300" style="background-color: var(--card-bg); transition: background-color 0.4s;">
        <div class="flex items-center gap-3">
            <img src="https://static.wixstatic.com/media/ce35a6_6238472a58874e879580b1984889e892~mv2.jpeg/v1/fill/w_212,h_147,al_c,q_80,usm_0.66_1.00_0.01,enc_avif,quality_auto/logo.jpeg" alt="Logo Universidad Galileo" class="h-10 md:h-12 w-auto rounded-md shadow-sm">
            <h1 class="text-xl md:text-2xl font-extrabold tracking-wider bg-gradient-to-r from-blue-500 to-indigo-500 bg-clip-text text-transparent">Logística Pro</h1>
        </div>

        <!-- Menú de navegación visible únicamente en versión Escritorio (md:flex) -->
        <nav class="hidden md:flex items-center gap-6 font-semibold">
            <button onclick="switchTab('inicio')" id="desk-nav-inicio" class="text-indigo-500 dark:text-indigo-400 hover:text-indigo-600 transition-colors">Inicio</button>
            <button onclick="switchTab('tienda')" id="desk-nav-tienda" class="text-slate-500 dark:text-slate-400 hover:text-indigo-500 transition-colors">Tienda</button>
            <button onclick="switchTab('mapa')" id="desk-nav-mapa" class="text-slate-500 dark:text-slate-400 hover:text-indigo-500 transition-colors">Mapa</button>
            <button onclick="switchTab('recursos')" id="desk-nav-recursos" class="text-slate-500 dark:text-slate-400 hover:text-indigo-500 transition-colors">Autor</button>
            <button onclick="salirPlataforma()" class="text-red-400 hover:text-red-500 transition-colors">Salir</button>
        </nav>

        <button id="themeToggle" class="bg-indigo-100 hover:bg-indigo-200 dark:bg-slate-800 dark:hover:bg-slate-700 p-2.5 rounded-full transition-all duration-300 text-slate-800 dark:text-indigo-200">
            <span id="themeIcon">🌙</span>
        </button>
    </header>

    <!-- Contenido Principal con Ancho Máximo en PC y Fluido en Móviles -->
    <main class="flex-grow max-w-6xl w-full mx-auto p-4 md:p-8 space-y-6" id="scrollContainer">
        
        <!-- PESTAÑA 1: INICIO (Bienvenida) -->
        <div id="tab-inicio" class="tab-content active">
            <section id="bienvenida" class="contenedor-seccion p-6 md:p-10 shadow-sm flex flex-col md:flex-row items-center gap-8">
                <div class="flex-shrink-0">
                    <img src="https://i.pinimg.com/736x/9e/96/02/9e9602badbbb86942b3681d31909e608.jpg" 
                         alt="Ilustración Logística y Transporte" 
                         class="h-44 w-44 md:h-56 md:w-56 object-cover rounded-2xl shadow-md border-4 border-indigo-100 dark:border-slate-700">
                </div>
                
                <div class="flex-grow text-center md:text-left space-y-3">
                    <span class="text-xs font-bold uppercase tracking-widest px-3 py-1 rounded-full bg-indigo-100 dark:bg-slate-800" style="color: var(--welcome-text);">Plataforma Logística</span>
                    
                    <h2 class="text-3xl md:text-4xl font-extrabold transition-colors duration-300" style="color: var(--welcome-text); text-shadow: 1px 1px 1px rgba(0,0,0,0.15);">
                        Bienvenida a la Red Global
                    </h2>
                    
                    <p class="text-sm md:text-base opacity-100 leading-relaxed transition-colors duration-300" style="color: var(--welcome-text); text-shadow: 0.5px 0.5px 1px rgba(0,0,0,0.1);">
                        <strong>Misión:</strong> Nuestra misión es optimizar las cadenas de suministro mediante integraciones tecnológicas de vanguardia, garantizando trazabilidad en tiempo real, reducción de costos y entrega puntual en cada destino de la red global.
                    </p>
                    
                    <button onclick="leerEslogan()" class="enlace-interactivo btn-secundario text-sm flex items-center gap-1.5 transform active:scale-95 py-2.5 px-6 mx-auto md:mx-0">
                        🔊 Escuchar Misión / Eslogan
                    </button>
                </div>
            </section>
        </div>

        <!-- PESTAÑA 2: TIENDA (Registro de Carga) -->
        <div id="tab-tienda" class="tab-content">
            <section id="tienda" class="contenedor-seccion p-6 shadow-sm space-y-6">
                <h2 class="text-2xl font-bold border-b pb-2 border-dashed border-slate-300 dark:border-slate-600">Registro de Carga</h2>
                
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-start">
                    <form id="formularioCarga" class="space-y-4">
                        <div>
                            <label class="block text-sm font-semibold mb-1 opacity-90" for="nombreCliente">Nombre del Cliente / Empresa:</label>
                            <input type="text" id="nombreCliente" class="w-full px-4 py-2.5 rounded-xl border border-slate-300 dark:border-slate-600 focus:ring-2 focus:ring-indigo-400 focus:outline-none bg-slate-50 dark:bg-slate-800 text-slate-800 dark:text-white transition-colors" placeholder="Ej. Logística Global SA">
                        </div>
                        <div>
                            <label class="block text-sm font-semibold mb-1 opacity-90" for="volumenCarga">Volumen de Carga (Metros Cúbicos):</label>
                            <input type="number" id="volumenCarga" oninput="actualizarEstimacionTransito()" class="w-full px-4 py-2.5 rounded-xl border border-slate-300 dark:border-slate-600 focus:ring-2 focus:ring-indigo-400 focus:outline-none bg-slate-50 dark:bg-slate-800 text-slate-800 dark:text-white transition-colors" placeholder="Ej. 150">
                        </div>
                        <button type="submit" class="w-full enlace-interactivo justify-center font-bold py-3">
                            Registrar Envío
                        </button>
                    </form>

                    <!-- Tarjeta de Estimación de Tránsito -->
                    <div class="p-6 rounded-2xl border-2 border-dashed border-indigo-200 dark:border-slate-700 bg-indigo-50 bg-opacity-30 dark:bg-slate-800/50 flex flex-col justify-between min-h-[220px]">
                        <div>
                            <h3 class="text-lg font-bold text-slate-800 dark:text-slate-100 flex items-center gap-2 mb-2">
                                <span>⏱️</span> Tránsito Estimado de Distribución
                            </h3>
                            <p class="text-xs text-slate-500 dark:text-slate-400 mb-4 leading-relaxed">
                                Cálculo heurístico en base al volumen de carga, origen del remitente y despacho hacia el centro logístico final (Universidad Galileo, Zona 10).
                            </p>
                        </div>
                        <div class="bg-white dark:bg-slate-800 p-4 rounded-xl border border-slate-200 dark:border-slate-700 flex items-center justify-between">
                            <div>
                                <span class="text-xs font-semibold uppercase tracking-wider text-slate-400 block">Tiempo de entrega</span>
                                <span id="textoDiasEstimados" class="text-2xl font-extrabold text-indigo-600 dark:text-indigo-400">2 días hábiles</span>
                            </div>
                            <div class="text-3xl" id="iconoEstimado">🚚</div>
                        </div>
                        <p class="text-[11px] opacity-75 mt-2 italic text-slate-600 dark:text-slate-400" id="notaEstimacion">
                            *Usa la pestaña 📍 Mapa para activar la geolocalización satelital.
                        </p>
                    </div>
                </div>
            </section>
        </div>

        <!-- PESTAÑA 3: MAPA (Geolocalización) -->
        <div id="tab-mapa" class="tab-content">
            <section id="geolocalizacion" class="contenedor-seccion p-6 shadow-sm text-center">
                <h2 class="text-2xl font-bold mb-3 border-b pb-2 border-dashed border-slate-300 dark:border-slate-600">Almacén de Origen</h2>
                <p class="text-sm mb-4 opacity-80 leading-relaxed">Localiza tu origen en el GPS para trazar la ruta hacia la Universidad Galileo (Zona 10).</p>
                <button onclick="solicitarPermisoGPS()" class="enlace-interactivo btn-secundario py-3 px-8 transform active:scale-95 mb-6">
                    📍 Capturar Ubicación GPS
                </button>
                <div id="resultadoUbicacion" class="text-sm font-mono p-4 bg-slate-100 dark:bg-slate-800 rounded-2xl hidden border border-slate-200 dark:border-slate-700">
                    <!-- Mapa y coordenadas -->
                </div>
            </section>
        </div>

        <!-- PESTAÑA 4: AUTORÍA (Enlaces, Canvas e Interactividad) -->
        <div id="tab-recursos" class="tab-content">
            <section id="enlaces" class="contenedor-seccion p-6 shadow-sm space-y-6">
                <h2 class="text-2xl font-bold border-b pb-2 border-dashed border-slate-300 dark:border-slate-600">Autoría y Enlaces</h2>
                
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
                    <!-- Canvas -->
                    <div class="flex flex-col items-center justify-center">
                        <canvas id="miCanvas" width="320" height="130" class="border-2 border-dashed border-indigo-200 dark:border-slate-600 rounded-2xl bg-indigo-50 bg-opacity-30 dark:bg-slate-800 shadow-inner"></canvas>
                        <p class="text-xs mt-2 opacity-75">Canvas API - Animación Dinámica</p>
                    </div>

                    <!-- Enlaces Interactivos -->
                    <div class="flex flex-col gap-3">
                        <a href="https://robertotelon.wixsite.com/my-site-5" target="_blank" class="enlace-interactivo justify-between">
                            <span>🌐 Mi Sitio en Wix (T14)</span>
                            <span class="text-xs bg-white bg-opacity-30 px-2 py-0.5 rounded-full">Abrir</span>
                        </a>
                        <a href="https://www.youtube.com/watch?v=a5MttjQpu5g" target="_blank" class="enlace-interactivo justify-between" style="background-color: #fca5a5; color: #7f1d1d;">
                            <span>▶️ Video en YouTube</span>
                            <span class="text-xs bg-white bg-opacity-45 px-2 py-0.5 rounded-full">Ver</span>
                        </a>
                        <a href="#" onclick="mostrarSubpaginaRedes(event)" class="enlace-interactivo justify-between" style="background-color: #bae6fd; color: #0369a1;">
                            <span>📱 Redes Sociales (T15)</span>
                            <span class="text-xs bg-white bg-opacity-45 px-2 py-0.5 rounded-full">Abrir</span>
                        </a>
                        <a href="https://www.galileo.edu/" target="_blank" class="enlace-interactivo justify-between" style="background-color: #fed7aa; color: #7c2d12;">
                            <span class="flex gap-2 items-center">
                                <svg class="w-5 h-5 bg-white rounded-full p-0.5" viewBox="0 0 24 24" fill="#ea580c"><path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"/></svg>
                                Universidad Galileo
                            </span>
                            <span class="text-xs bg-white bg-opacity-45 px-2 py-0.5 rounded-full">Portal</span>
                        </a>
                    </div>
                </div>
            </section>
        </div>

        <!-- SUBPÁGINA REDES SOCIALES -->
        <div id="subpaginaRedes" class="tab-content">
            <section class="contenedor-seccion p-6 md:p-8 shadow-sm text-center max-w-2xl mx-auto">
                <h2 class="text-2xl md:text-3xl font-extrabold mb-1 text-indigo-500 dark:text-indigo-400">Canales Oficiales</h2>
                <p class="text-sm mb-6 opacity-70">Conéctate con soporte global</p>
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 mb-6">
                    <a href="https://www.facebook.com/" target="_blank" class="enlace-interactivo justify-center py-4 border-none" style="background-color: #bfdbfe; color: #1e40af;">
                        📘 Facebook
                    </a>
                    <a href="https://www.instagram.com/" target="_blank" class="enlace-interactivo justify-center py-4 border-none" style="background-color: #fbcfe8; color: #9d174d;">
                        📸 Instagram
                    </a>
                    <a href="https://x.com/" target="_blank" class="enlace-interactivo justify-center py-4 border-none" style="background-color: #e2e8f0; color: #0f172a;">
                        𝕏 X (Twitter)
                    </a>
                    <a href="https://www.tiktok.com/" target="_blank" class="enlace-interactivo justify-center py-4 border-none" style="background-color: #ccfbf1; color: #115e59;">
                        🎵 TikTok
                    </a>
                </div>
                <button onclick="ocultarSubpaginaRedes()" class="bg-slate-200 hover:bg-slate-300 dark:bg-slate-700 dark:hover:bg-slate-600 text-slate-800 dark:text-white px-8 py-3 rounded-full font-bold text-sm transition-all w-full sm:w-auto">
                    ⬅️ Volver a Recursos
                </button>
            </section>
        </div>

        <!-- Pantalla de Despedida / Salida Activa (Oculta por defecto) -->
        <section id="pantallaSalida" class="contenedor-seccion rounded-2xl p-8 shadow-2xl text-center max-w-md mx-auto border-t-4 border-t-red-400 hidden">
            <div class="w-20 h-20 bg-red-100 dark:bg-red-950/40 rounded-full flex items-center justify-center mx-auto mb-6">
                <span class="text-4xl">🚪</span>
            </div>
            <h2 class="text-3xl font-extrabold mb-3 text-rose-500 dark:text-rose-400">¡Sesión Finalizada!</h2>
            <p class="text-slate-600 dark:text-slate-300 mb-6 text-sm leading-relaxed">
                Has salido de forma segura de la plataforma **Logística Pro**. Toda la cola de distribución y datos de geolocalización temporal han sido eliminados de tu navegador con éxito.
            </p>
            <button onclick="reiniciarPlataforma()" class="enlace-interactivo justify-center bg-emerald-200 text-emerald-900 border-emerald-300 font-bold px-6 py-2.5 rounded-full hover:bg-emerald-300 transition-all">
                🔄 Reingresar a la Plataforma
            </button>
        </section>

    </main>

    <!-- Barra de Navegación Inferior (Visible solo en móviles `md:hidden`) -->
    <nav class="md:hidden border-t border-opacity-10 border-slate-300 py-2.5 px-2 flex justify-around items-center sticky bottom-0 z-40 w-full" style="background-color: var(--card-bg); transition: background-color 0.4s;">
        <!-- Tab Inicio -->
        <button onclick="switchTab('inicio')" id="nav-inicio" class="flex flex-col items-center gap-1 text-indigo-500 dark:text-indigo-400">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                <path stroke-linecap="round" stroke-linejoin="round" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6" />
            </svg>
            <span class="text-[10px] font-semibold">Inicio</span>
        </button>
        <!-- Tab Tienda -->
        <button onclick="switchTab('tienda')" id="nav-tienda" class="flex flex-col items-center gap-1 text-slate-400">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                <path stroke-linecap="round" stroke-linejoin="round" d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z" />
            </svg>
            <span class="text-[10px] font-semibold">Tienda</span>
        </button>
        <!-- Tab Geolocalización -->
        <button onclick="switchTab('mapa')" id="nav-mapa" class="flex flex-col items-center gap-1 text-slate-400">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                <path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                <path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
            </svg>
            <span class="text-[10px] font-semibold">Mapa</span>
        </button>
        <!-- Tab Autoría -->
        <button onclick="switchTab('recursos')" id="nav-recursos" class="flex flex-col items-center gap-1 text-slate-400">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                <path stroke-linecap="round" stroke-linejoin="round" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z" />
            </svg>
            <span class="text-[10px] font-semibold">Autor</span>
        </button>
        <!-- Botón Salir -->
        <button onclick="salirPlataforma()" class="flex flex-col items-center gap-1 text-red-400 hover:text-red-500">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                <path stroke-linecap="round" stroke-linejoin="round" d="M17 16l4-4m0 0l-4-4m4 4H7m6 4v1a3 3 0 01-3 3H6a3 3 0 01-3-3V7a3 3 0 013-3h4a3 3 0 013 3v1" />
            </svg>
            <span class="text-[10px] font-semibold">Salir</span>
        </button>
    </nav>

    <!-- Footer Clásico (Visible únicamente en versión Escritorio) -->
    <footer id="footerClasico" class="hidden md:flex bg-slate-900 text-slate-300 py-6 text-center flex-col items-center justify-center gap-4 px-4 w-full">
        <div>
            <p class="mb-1 font-semibold">&copy; 2026 - Proyecto: examenA_25000701.</p>
            <p class="text-xs opacity-70">Logística y Cadenas de Suministro | Guatemala</p>
        </div>

        <div class="flex items-center justify-center gap-4">
            <!-- Logotipo SVG Vectorial de Transporte -->
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round" class="h-10 w-10 text-rose-400 dark:text-rose-300 bg-rose-50 dark:bg-slate-800 p-2 rounded-xl border border-rose-200 dark:border-slate-700 shadow-md">
                <rect x="1" y="3" width="15" height="13" rx="2" ry="2" />
                <polygon points="16 8 20 8 23 11 23 16 16 16 16 8" />
                <circle cx="5.5" cy="18.5" r="2.5" />
                <circle cx="18.5" cy="18.5" r="2.5" />
                <path d="M18 4l2 2 4-4" stroke="#10b981" />
            </svg>
        </div>
    </footer>

    <!-- Modales -->
    <div id="customModal" class="fixed inset-0 z-50 flex items-center justify-center hidden">
        <div class="bg-white dark:bg-slate-800 p-6 rounded-2xl shadow-2xl max-w-sm w-full mx-4 border border-slate-200 dark:border-slate-700 text-center">
            <h3 id="modalTitle" class="text-lg font-bold mb-2 text-slate-900 dark:text-white">Notificación</h3>
            <p id="modalMessage" class="text-slate-600 dark:text-slate-300 mb-5 text-sm leading-relaxed"></p>
            <button onclick="cerrarModal()" class="w-full enlist-interactivo justify-center font-bold py-2.5 px-4 rounded-xl border-none text-xs enlace-interactivo">
                Aceptar
            </button>
        </div>
    </div>

    <div id="confirmModal" class="fixed inset-0 z-50 flex items-center justify-center hidden animate-fade-in">
        <div class="bg-white dark:bg-slate-800 p-6 rounded-2xl shadow-2xl max-w-sm w-full mx-4 border border-slate-200 dark:border-slate-700 text-center">
            <h3 class="text-lg font-bold mb-2 text-slate-900 dark:text-white flex items-center justify-center gap-1.5">
                <span>📍 Permiso GPS</span>
            </h3>
            <p class="text-slate-600 dark:text-slate-300 mb-5 text-sm leading-relaxed">¿Autoriza a la aplicación a utilizar el GPS para calcular la ruta exacta de distribución hacia la Universidad Galileo?</p>
            <div class="flex gap-4">
                <button onclick="ejecutarGPS()" class="w-full bg-emerald-200 hover:bg-emerald-300 text-emerald-900 font-bold py-2.5 px-4 rounded-xl text-xs border border-emerald-300">
                    Sí, permitir
                </button>
                <button onclick="cerrarConfirmModal()" class="w-full bg-rose-200 hover:bg-rose-300 text-rose-900 font-bold py-2.5 px-4 rounded-xl text-xs border border-rose-300">
                    No, cancelar
                </button>
            </div>
        </div>
    </div>

    <!-- SCRIPTS LÓGICOS -->
    <script>
        // --- Variables Globales de Ubicación ---
        let userLat = null;
        let userLon = null;
        const galileoCoords = { lat: 14.603808, lon: -90.505215 };

        // --- SISTEMA DE PESTAÑAS (TABS) ---
        function switchTab(tabId) {
            // Ocultar todas las pestañas de contenido
            const tabs = document.querySelectorAll('.tab-content');
            tabs.forEach(tab => tab.classList.remove('active'));

            // Quitar estilos activos de los botones (Bottom Nav - Móviles)
            const navButtons = document.querySelectorAll('nav button');
            navButtons.forEach(btn => {
                btn.classList.remove('text-indigo-500', 'dark:text-indigo-400');
                btn.classList.add('text-slate-400');
            });

            // Quitar estilos activos de los botones (Top Nav - Escritorios)
            const deskButtons = document.querySelectorAll('header nav button');
            deskButtons.forEach(btn => {
                btn.classList.remove('text-indigo-500', 'dark:text-indigo-400');
                btn.classList.add('text-slate-500', 'dark:text-slate-400');
            });

            // Activar el contenedor de contenido seleccionado
            document.getElementById(`tab-${tabId}`).classList.add('active');
            
            // Pintar activo el botón móvil
            const activeBtn = document.getElementById(`nav-${tabId}`);
            if (activeBtn) {
                activeBtn.classList.remove('text-slate-400');
                activeBtn.classList.add('text-indigo-500', 'dark:text-indigo-400');
            }

            // Pintar activo el botón de escritorio
            const activeDeskBtn = document.getElementById(`desk-nav-${tabId}`);
            if (activeDeskBtn) {
                activeDeskBtn.classList.remove('text-slate-500', 'dark:text-slate-400');
                activeDeskBtn.classList.add('text-indigo-500', 'dark:text-indigo-400');
            }

            // Hacer scroll suave al inicio
            window.scrollTo({top: 0, behavior: 'smooth'});
        }

        // --- 1. Modo Claro / Oscuro ---
        const themeToggle = document.getElementById('themeToggle');
        const themeIcon = document.getElementById('themeIcon');
        const body = document.body;

        themeToggle.addEventListener('click', () => {
            body.classList.toggle('dark');
            const isDark = body.classList.contains('dark');
            themeIcon.textContent = isDark ? '☀️' : '🌙';
            dibujarNombreEnCanvas();
        });

        // --- 2. Funciones de Modal Personalizado ---
        const modal = document.getElementById('customModal');
        const modalTitle = document.getElementById('modalTitle');
        const modalMessage = document.getElementById('modalMessage');

        function mostrarModal(titulo, mensaje) {
            modalTitle.textContent = titulo;
            modalMessage.textContent = mensaje;
            modal.classList.remove('hidden');
        }

        function cerrarModal() {
            modal.classList.add('hidden');
        }

        // --- 3. Web Speech API ---
        function leerEslogan() {
            const eslogan = "Nuestra misión es optimizar las cadenas de suministro mediante integraciones tecnológicas de vanguardia, garantizando trazabilidad en tiempo real, reducción de costos y entrega puntual en cada destino de la red global.";
            if ('speechSynthesis' in window) {
                window.speechSynthesis.cancel();
                const utterance = new SpeechSynthesisUtterance(eslogan);
                utterance.lang = 'es-ES';
                utterance.rate = 0.95;
                window.speechSynthesis.speak(utterance);
            } else {
                mostrarModal('Error', 'Tu dispositivo no soporta la síntesis de voz de Web Speech API.');
            }
        }

        // --- Heurística de cálculo de días de tránsito ---
        function calcularDiasDeTransito() {
            const volumenInput = document.getElementById('volumenCarga').value;
            const volumen = parseFloat(volumenInput) || 0;
            let diasBase = 2;

            if (userLat !== null && userLon !== null) {
                const distKm = calcularDistanciaHaversine(userLat, userLon, galileoCoords.lat, galileoCoords.lon);
                if (distKm < 15) {
                    diasBase = 1;
                } else if (distKm >= 15 && distKm < 80) {
                    diasBase = 2;
                } else if (distKm >= 80 && distKm < 250) {
                    diasBase = 3;
                } else {
                    diasBase = 5;
                }
            }

            if (volumen > 100 && volumen <= 500) {
                diasBase += 1;
            } else if (volumen > 500) {
                diasBase += 2;
            }
            return diasBase;
        }

        function calcularDistanciaHaversine(lat1, lon1, lat2, lon2) {
            const R = 6371;
            const dLat = (lat2 - lat1) * (Math.PI / 180);
            const dLon = (lon2 - lon1) * (Math.PI / 180);
            const a = 
                Math.sin(dLat/2) * Math.sin(dLat/2) +
                Math.cos(lat1 * (Math.PI / 180)) * Math.cos(lat2 * (Math.PI / 180)) * Math.sin(dLon/2) * Math.sin(dLon/2); 
            const c = 2 * Math.atan2(Math.sqrt(a), Math.sqrt(1-a)); 
            return R * c;
        }

        function actualizarEstimacionTransito() {
            const dias = calcularDiasDeTransito();
            const textoDias = document.getElementById('textoDiasEstimados');
            const iconoEstimado = document.getElementById('iconoEstimado');
            const notaEstimacion = document.getElementById('notaEstimacion');
            const volumen = parseFloat(document.getElementById('volumenCarga').value) || 0;

            textoDias.textContent = `${dias} ${dias === 1 ? 'día hábil' : 'días hábiles'}`;
            iconoEstimado.textContent = dias <= 1 ? '⚡' : (volumen > 100 ? '🚛' : '📦');

            if (userLat !== null && userLon !== null) {
                const dist = calcularDistanciaHaversine(userLat, userLon, galileoCoords.lat, galileoCoords.lon).toFixed(1);
                notaEstimacion.textContent = `*Cálculo satelital activo. Distancia al destino: ${dist} km. Volumen: ${volumen} m³.`;
            } else {
                notaEstimacion.textContent = `*Cálculo local estándar. Captura el GPS del almacén de origen para trazar la ruta exacta.`;
            }
        }

        // --- 4. Validación de Formulario (Tienda) ---
        const form = document.getElementById('formularioCarga');
        form.addEventListener('submit', function(e) {
            e.preventDefault();
            const nombre = document.getElementById('nombreCliente').value.trim();
            const volumen = document.getElementById('volumenCarga').value.trim();

            if (nombre === '' || volumen === '') {
                mostrarModal('Validación', 'Complete todos los campos del envío para continuar.');
            } else if (volumen <= 0) {
                mostrarModal('Error', 'El volumen de carga debe ser mayor a 0 m³.');
            } else {
                const diasTransito = calcularDiasDeTransito();
                mostrarModal(
                    'Registro Exitoso', 
                    `¡Hola, ${nombre}! Tu envío de ${volumen} m³ ha sido registrado con éxito. Tránsito estimado hacia la Universidad Galileo: ${diasTransito} ${diasTransito === 1 ? 'día' : 'días'}.`
                );
                form.reset();
                actualizarEstimacionTransito();
            }
        });

        // --- 5. Geolocalización API ---
        function solicitarPermisoGPS() {
            document.getElementById('confirmModal').classList.remove('hidden');
        }

        function cerrarConfirmModal() {
            document.getElementById('confirmModal').classList.add('hidden');
            const resultadoDiv = document.getElementById('resultadoUbicacion');
            resultadoDiv.classList.remove('hidden');
            resultadoDiv.innerHTML = '<span class="text-rose-500 font-semibold">❌ Acceso GPS cancelado por el usuario.</span>';
        }

        function ejecutarGPS() {
            document.getElementById('confirmModal').classList.add('hidden');
            obtenerUbicacion();
        }

        function obtenerUbicacion() {
            const resultadoDiv = document.getElementById('resultadoUbicacion');
            resultadoDiv.classList.remove('hidden');
            resultadoDiv.innerHTML = '<span class="animate-pulse text-indigo-500 font-semibold">📍 Solicitando GPS del sistema y trazando ruta...</span>';

            if ("geolocation" in navigator) {
                navigator.geolocation.getCurrentPosition(
                    (position) => {
                        userLat = position.coords.latitude;
                        userLon = position.coords.longitude;
                        actualizarEstimacionTransito();

                        const mapUrl = `https://maps.google.com/maps?q=${userLat.toFixed(6)},${userLon.toFixed(6)}&z=15&output=embed`;

                        resultadoDiv.innerHTML = `
                            <div class="text-left space-y-4 font-sans text-xs md:text-sm">
                                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                    <div class="p-4 bg-emerald-50 dark:bg-emerald-950/40 rounded-xl border border-emerald-200">
                                        <span class="text-emerald-800 dark:text-emerald-200 font-bold block mb-1">✅ Origen Capturado (Tu ubicación actual)</span>
                                        <p class="text-[11px] md:text-xs">Lat: ${userLat.toFixed(5)} | Lon: ${userLon.toFixed(5)}</p>
                                    </div>
                                    <div class="p-4 bg-sky-50 dark:bg-sky-950/40 rounded-xl border border-sky-200">
                                        <span class="text-sky-800 dark:text-sky-200 font-bold block mb-1">🏢 Destino Logístico</span>
                                        <p class="text-[11px] md:text-xs">Universidad Galileo, 7a Avenida, Calle Dr. Eduardo Suger, Zona 10.</p>
                                    </div>
                                </div>
                                <div class="w-full h-64 md:h-80 rounded-2xl overflow-hidden border border-slate-200 shadow-inner">
                                    <iframe width="100%" height="100%" frameborder="0" src="${mapUrl}"></iframe>
                                </div>
                            </div>
                        `;
                    },
                    (error) => {
                        resultadoDiv.innerHTML = `<span class="text-rose-500">Error de GPS: ${error.message}</span>`;
                    }
                );
            } else {
                resultadoDiv.innerHTML = '<span class="text-rose-500">La geolocalización no es soportada por este dispositivo.</span>';
            }
        }

        // --- SUBPÁGINA REDES SOCIALES ---
        function mostrarSubpaginaRedes(e) {
            e.preventDefault();
            document.getElementById('tab-recursos').classList.remove('active');
            document.getElementById('subpaginaRedes').classList.add('active');
        }

        function ocultarSubpaginaRedes() {
            document.getElementById('subpaginaRedes').classList.remove('active');
            document.getElementById('tab-recursos').classList.add('active');
        }

        // --- SISTEMA DE SALIDA DE LA PLATAFORMA ---
        function salirPlataforma() {
            if ('speechSynthesis' in window) {
                window.speechSynthesis.cancel();
            }
            form.reset();
            userLat = null;
            userLon = null;
            const resultadoDiv = document.getElementById('resultadoUbicacion');
            resultadoDiv.innerHTML = '';
            resultadoDiv.classList.add('hidden');
            actualizarEstimacionTransito();

            // Ocultar barras de navegación y headers
            document.querySelector('nav').classList.add('hidden');
            document.querySelector('header nav').classList.add('hidden');
            document.getElementById('footerClasico').classList.add('hidden');

            const activeTab = document.querySelector('.tab-content.active');
            if (activeTab) activeTab.classList.remove('active');

            document.getElementById('pantallaSalida').classList.remove('hidden');
        }

        function reiniciarPlataforma() {
            document.querySelector('nav').classList.remove('hidden');
            document.querySelector('header nav').classList.remove('hidden');
            document.getElementById('footerClasico').classList.remove('hidden');
            document.getElementById('pantallaSalida').classList.add('hidden');
            switchTab('inicio');
        }

        // --- 6. Canvas API (Firma "ISMATUL" con Movimiento Creativo Pastel) ---
        let animacionCanvasId;
        let tiempoAnimacion = 0;

        function dibujarNombreEnCanvas() {
            const canvas = document.getElementById('miCanvas');
            if (!canvas) return;
            const ctx = canvas.getContext('2d');
            
            if (animacionCanvasId) {
                cancelAnimationFrame(animacionCanvasId);
            }

            function animar() {
                ctx.clearRect(0, 0, canvas.width, canvas.height);
                const isDark = document.body.classList.contains('dark');
                
                ctx.fillStyle = isDark ? '#1e293b' : '#f8fafc';
                ctx.fillRect(10, 10, canvas.width - 20, canvas.height - 20);

                ctx.strokeStyle = isDark ? '#334155' : '#e2e8f0';
                ctx.lineWidth = 1.5;
                ctx.strokeRect(12, 12, canvas.width - 24, canvas.height - 24);

                const texto = "ISMATUL";
                ctx.font = 'bold 36px "Segoe UI", sans-serif';
                ctx.textAlign = 'center';
                ctx.textBaseline = 'middle';
                
                let anchoTotal = 0;
                for(let i = 0; i < texto.length; i++) {
                    anchoTotal += ctx.measureText(texto[i]).width + 4;
                }
                let startX = (canvas.width - anchoTotal) / 2 + 8;

                for (let i = 0; i < texto.length; i++) {
                    const char = texto[i];
                    const offsetY = Math.sin(tiempoAnimacion + i * 0.6) * 12;
                    const hue = (tiempoAnimacion * 50 + i * 35) % 360;
                    
                    ctx.fillStyle = `hsl(${hue}, 80%, ${isDark ? 75 : 55}%)`;
                    
                    ctx.shadowColor = isDark ? 'rgba(0,0,0,0.5)' : 'rgba(129, 140, 248, 0.15)';
                    ctx.shadowBlur = 4;
                    ctx.shadowOffsetX = 2;
                    ctx.shadowOffsetY = 2;

                    ctx.fillText(char, startX, canvas.height / 2 + offsetY);
                    
                    ctx.shadowBlur = 0;
                    ctx.shadowOffsetX = 0;
                    ctx.shadowOffsetY = 0;

                    startX += ctx.measureText(char).width + 4;
                }

                tiempoAnimacion += 0.04;
                animacionCanvasId = requestAnimationFrame(animar);
            }
            animar();
        }

        // --- 7. Service Worker (Blob dynamic URL para compatibilidad local) ---
        function registrarPWA() {
            if ('serviceWorker' in navigator) {
                const swContent = `
                    const CACHE_NAME = 'logistica-pro-v4';
                    const ASSETS_TO_CACHE = ['./', './index.html', './manifest.json'];

                    self.addEventListener('install', (e) => {
                        e.waitUntil(caches.open(CACHE_NAME).then(c => c.addAll(ASSETS_TO_CACHE).catch(() => {})));
                        self.skipWaiting();
                    });

                    self.addEventListener('activate', (e) => {
                        e.waitUntil(caches.keys().then(keys => Promise.all(keys.map(k => k !== CACHE_NAME && caches.delete(k)))));
                        return self.clients.claim();
                    });

                    self.addEventListener('fetch', (e) => {
                        e.respondWith(caches.match(e.request).then(r => r || fetch(e.request).catch(() => new Response("Offline"))));
                    });
                `;

                try {
                    const blob = new Blob([swContent], { type: 'application/javascript' });
                    const swBlobUrl = URL.createObjectURL(blob);
                    window.addEventListener('load', () => {
                        navigator.serviceWorker.register(swBlobUrl).catch(() => {
                            navigator.serviceWorker.register('sw.js').catch(() => {});
                        });
                    });
                } catch (e) {}
            }
        }

        document.addEventListener('DOMContentLoaded', () => {
            dibujarNombreEnCanvas();
            registrarPWA();
            actualizarEstimacionTransito();
        });

    </script>
</body>
</html>