[index.html](https://github.com/user-attachments/files/24871052/index.html)
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Consultora Trama Territorios | Economía Solidaria y Oficios</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');
        
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
        }

        .hero-gradient {
            /* Ruta local a la carpeta img */
            background: linear-gradient(rgba(15, 23, 42, 0.8), rgba(15, 23, 42, 0.8)), 
                        url('img/fondo-inicio.jpg');
            background-size: cover;
            background-position: center;
        }

        .card-hover:hover {
            transform: translateY(-5px);
            transition: all 0.3s ease;
        }

        .whatsapp-float {
            position: fixed;
            bottom: 30px;
            right: 30px;
            background-color: #25d366;
            color: white;
            width: 60px;
            height: 60px;
            border-radius: 50px;
            text-align: center;
            font-size: 30px;
            box-shadow: 2px 2px 10px rgba(0,0,0,0.2);
            z-index: 100;
            display: flex;
            align-items: center;
            justify-content: center;
            text-decoration: none;
            transition: transform 0.3s ease;
        }
        
        .whatsapp-float:hover {
            transform: scale(1.1);
            background-color: #128c7e;
        }

        .nav-logo {
            max-height: 80px; 
            width: auto;
            display: block;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800">

    <!-- Navegación -->
    <nav class="bg-white shadow-md sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-24 items-center">
                <div class="flex-shrink-0 flex items-center">
                    <!-- Ruta local a la carpeta img para el logo -->
                    <img src="img/image_ac78f4.jpg" alt="Logo Consultora Trama Territorios" class="nav-logo">
                </div>
                <div class="hidden md:block">
                    <div class="ml-10 flex items-baseline space-x-8 font-medium">
                        <a href="#inicio" class="text-blue-900 hover:text-blue-600 px-3 py-2 transition">Inicio</a>
                        <a href="#servicios" class="text-slate-600 hover:text-blue-600 px-3 py-2 transition">Servicios</a>
                        <a href="#nosotros" class="text-slate-600 hover:text-blue-600 px-3 py-2 transition">Nosotros</a>
                        <a href="#acciones" class="text-slate-600 hover:text-blue-600 px-3 py-2 transition">Novedades</a>
                        <a href="#contacto" class="bg-blue-600 text-white px-5 py-2 rounded-full hover:bg-blue-700 transition">Contactanos</a>
                    </div>
                </div>
                <div class="md:hidden">
                    <button id="mobile-menu-button" class="text-slate-600 hover:text-blue-600 focus:outline-none">
                        <i class="fa-solid fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
        </div>
        <!-- Menú Móvil -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-t border-slate-100 px-4 py-4 space-y-2">
            <a href="#inicio" class="block text-slate-600 py-2">Inicio</a>
            <a href="#servicios" class="block text-slate-600 py-2">Servicios</a>
            <a href="#nosotros" class="block text-slate-600 py-2">Nosotros</a>
            <a href="#acciones" class="block text-slate-600 py-2">Novedades</a>
            <a href="#contacto" class="block text-blue-600 font-bold py-2">Contacto</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="inicio" class="hero-gradient min-h-[85vh] flex items-center text-white px-4 py-10">
        <div class="max-w-4xl mx-auto text-center">
            <h1 class="text-4xl md:text-6xl font-bold mb-6 leading-tight">
                Enseñamos a generar proyectos socioproductivos con anclaje en el aprendizaje de oficios y la economía solidaria
            </h1>
            <p class="text-xl md:text-2xl mb-10 text-slate-200">
                Consultoría experta en desarrollo territorial para América Latina.
            </p>
            <div class="flex flex-col sm:flex-row justify-center gap-4 flex-wrap">
                <a href="https://wa.me/5492954316211?text=Hola,%20me%20encantar%C3%ADa%20recibir%20mas%20asesoramiento%20sobre%20Trama%20Territorios!%20Muchas%20Gracias." target="_blank" class="bg-green-600 hover:bg-green-700 text-white px-6 py-4 rounded-full font-bold text-lg transition flex items-center justify-center gap-2">
                    <i class="fa-brands fa-whatsapp"></i> WhatsApp
                </a>
                <a href="https://www.instagram.com/trama_territorios/" target="_blank" class="bg-gradient-to-r from-pink-500 via-red-500 to-yellow-500 hover:from-pink-600 hover:via-red-600 hover:to-yellow-600 text-white px-6 py-4 rounded-full font-bold text-lg transition flex items-center justify-center gap-2">
                    <i class="fa-brands fa-instagram"></i> Instagram
                </a>
                <a href="https://www.linkedin.com/in/gladys-cruse%C3%B1o-b41779337/" target="_blank" class="bg-blue-700 hover:bg-blue-800 text-white px-6 py-4 rounded-full font-bold text-lg transition flex items-center justify-center gap-2">
                    <i class="fa-brands fa-linkedin"></i> LinkedIn
                </a>
            </div>
        </div>
    </section>

    <!-- Servicios -->
    <section id="servicios" class="py-20 px-4">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-blue-900 mb-4">Nuestros Servicios</h2>
                <div class="w-20 h-1 bg-blue-600 mx-auto"></div>
                <p class="mt-4 text-slate-600 max-w-2xl mx-auto">Soluciones integrales diseñadas para potenciar el desarrollo local y la economía social.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Servicio 1 -->
                <div class="bg-white p-8 rounded-2xl shadow-sm border border-slate-100 card-hover">
                    <div class="w-14 h-14 bg-blue-100 text-blue-600 rounded-xl flex items-center justify-center mb-6 text-2xl">
                        <i class="fa-solid fa-tools"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-blue-900">Enseñanza de oficios con base territorial</h3>
                    <p class="text-slate-600">Formación técnica adaptada a las necesidades reales de cada comunidad, impulsando la inserción laboral genuina.</p>
                </div>

                <!-- Servicio 2 -->
                <div class="bg-white p-8 rounded-2xl shadow-sm border border-slate-100 card-hover">
                    <div class="w-14 h-14 bg-blue-100 text-blue-600 rounded-xl flex items-center justify-center mb-6 text-2xl">
                        <i class="fa-solid fa-city"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-blue-900">Asesoramiento Institucional</h3>
                    <p class="text-slate-600">Apoyo a Municipios y organizaciones intermedias interesadas en incorporar modelos de economía solidaria en su gestión.</p>
                </div>

                <!-- Servicio 3 -->
                <div class="bg-white p-8 rounded-2xl shadow-sm border border-slate-100 card-hover">
                    <div class="w-14 h-14 bg-blue-100 text-blue-600 rounded-xl flex items-center justify-center mb-6 text-2xl">
                        <i class="fa-solid fa-chart-line"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-blue-900">Observatorios Sociales</h3>
                    <p class="text-xl font-semibold text-blue-900 opacity-0 group-hover:opacity-100">Creación y sostenimiento</p>
                    <p class="text-slate-600">Implementación de herramientas de diagnóstico y seguimiento para entender la realidad social de cada territorio.</p>
                </div>

                <!-- Servicio 4 -->
                <div class="bg-white p-8 rounded-2xl shadow-sm border border-slate-100 card-hover">
                    <div class="w-14 h-14 bg-blue-100 text-blue-600 rounded-xl flex items-center justify-center mb-6 text-2xl">
                        <i class="fa-solid fa-user-graduate"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-blue-900">Tutorías Especializadas</h3>
                    <p class="text-slate-600">Acompañamiento personalizado a estudiantes de nivel superior en carreras afines al desarrollo social.</p>
                </div>

                <!-- Servicio 5 -->
                <div class="bg-white p-8 rounded-2xl shadow-sm border border-slate-100 card-hover lg:col-span-1">
                    <div class="w-14 h-14 bg-blue-100 text-blue-600 rounded-xl flex items-center justify-center mb-6 text-2xl">
                        <i class="fa-solid fa-book-open"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-blue-900">Producción de Obras</h3>
                    <p class="text-slate-600">Edición y publicación de libros y material técnico sobre prospectiva y desarrollo territorial.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Por qué nosotros -->
    <section id="nosotros" class="py-20 bg-blue-900 text-white px-4">
        <div class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
            <div>
                <!-- NUEVO: Imagen de Gladys en formato circular -->
                <img src="img/fundadora.jpg" alt="Gladys Cruseño - Fundadora" class="w-40 h-40 rounded-full object-cover border-4 border-blue-400 shadow-lg mb-6">

                <span class="text-blue-400 font-bold uppercase tracking-wider mb-2 block">Nuestra Dirección</span>
                <h2 class="text-3xl md:text-5xl font-bold mb-6">Gladys Cruseño</h2>
                <h3 class="text-xl text-blue-200 mb-6 font-semibold">Experta en Desarrollo Territorial y Economía Social</h3>
                <p class="text-lg text-blue-50 mb-8 leading-relaxed">
                    "Nuestra fortaleza reside en el conocimiento profundo del trabajo en Territorio. Con más de 30 años de experiencia, sabemos desde dónde hablamos y proponemos. Somos expertos en prospectiva con un enfoque humano y solidario."
                </p>
                
                <div class="flex gap-4 mb-8">
                    <a href="https://www.linkedin.com/in/gladys-cruse%C3%B1o-b41779337/" target="_blank" class="inline-flex items-center gap-2 text-white border border-white/30 hover:bg-white/10 px-6 py-3 rounded-full transition">
                        <i class="fa-brands fa-linkedin text-xl"></i> Ver Trayectoria Profesional
                    </a>
                </div>

                <div class="grid grid-cols-2 gap-6 border-t border-white/10 pt-8">
                    <div>
                        <span class="block text-4xl font-bold text-white mb-1">30+</span>
                        <span class="text-blue-200 text-sm">Años de experiencia territorial</span>
                    </div>
                    <div>
                        <span class="block text-4xl font-bold text-white mb-1">LATAM</span>
                        <span class="text-blue-200 text-sm">Presencia online regional</span>
                    </div>
                </div>
            </div>
            <div class="space-y-4">
                <div class="bg-white/10 p-6 rounded-xl border border-white/10">
                    <h4 class="font-bold text-xl mb-2 flex items-center gap-3">
                        <i class="fa-solid fa-check-circle text-blue-400"></i> Trato Personalizado
                    </h4>
                    <p class="text-blue-100">Te escuchamos y trabajamos con vos mano a mano, adaptándonos a tu realidad local.</p>
                </div>
                <div class="bg-white/10 p-6 rounded-xl border border-white/10">
                    <h4 class="font-bold text-xl mb-2 flex items-center gap-3">
                        <i class="fa-solid fa-check-circle text-blue-400"></i> Inversión Módica
                    </h4>
                    <p class="text-blue-100">Al ser parte de la economía social, nuestros servicios son accesibles para comunas y organizaciones.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Sección Acciones (Blog/Noticias) -->
    <section id="acciones" class="py-20 px-4">
        <div class="max-w-7xl mx-auto">
            <div class="flex flex-col md:flex-row justify-between items-end mb-12">
                <div>
                    <!-- Cambio de título para reflejar "Novedades" -->
                    <h2 class="text-3xl md:text-4xl font-bold text-blue-900 mb-4">Novedades y Acciones Recientes</h2>
                    <div class="w-12 h-1 bg-blue-600 mb-4 md:mb-0"></div>
                </div>
                <!-- Botón destacado a Instagram -->
                <a href="https://www.instagram.com/trama_territorios/" target="_blank" class="group flex items-center gap-2 bg-gradient-to-r from-pink-500 via-red-500 to-yellow-500 text-white px-6 py-3 rounded-full font-bold shadow-md hover:shadow-lg transition">
                    <i class="fa-brands fa-instagram text-xl"></i> 
                    <span>Ver todas las novedades en Instagram</span>
                    <i class="fa-solid fa-arrow-right group-hover:translate-x-1 transition"></i>
                </a>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Noticia 1: Gestión de Proyectos -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-slate-100 transition hover:shadow-md">
                    <div class="h-48 bg-slate-200 overflow-hidden">
                        <!-- Ruta local a la carpeta img -->
                        <img src="img/noticia-taller.jpg" alt="Gestión de Proyectos" class="w-full h-full object-cover">
                    </div>
                    <div class="p-6">
                        <span class="text-blue-600 text-xs font-bold uppercase tracking-wider">Capacitación</span>
                        <h3 class="text-xl font-bold my-2 text-blue-900">Gestión de Proyectos Socioproductivos</h3>
                        <p class="text-slate-600 text-sm mb-4">Formación especializada en oficios (textil, gestión) con herramientas concretas para el desarrollo emprendedor.</p>
                        <a href="https://wa.me/5492954316211" class="text-blue-600 font-bold text-sm">Consultar próxima fecha</a>
                    </div>
                </div>

                <!-- Noticia 2: Asesoramiento -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-slate-100 transition hover:shadow-md">
                    <div class="h-48 bg-slate-200 overflow-hidden">
                        <!-- Ruta local a la carpeta img -->
                        <img src="img/noticia-asesoramiento.jpg" alt="Asesoramiento Municipal" class="w-full h-full object-cover">
                    </div>
                    <div class="p-6">
                        <span class="text-blue-600 text-xs font-bold uppercase tracking-wider">Municipios</span>
                        <h3 class="text-xl font-bold my-2 text-blue-900">Acompañamiento a la Gestión Local</h3>
                        <p class="text-slate-600 text-sm mb-4">Asesoramiento integral a comunas para el diseño e implementación de políticas de economía social.</p>
                        <a href="https://wa.me/5492954316211" class="text-blue-600 font-bold text-sm">Solicitar reunión</a>
                    </div>
                </div>

                <!-- Noticia 3: Publicaciones -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-slate-100 transition hover:shadow-md">
                    <div class="h-48 bg-slate-200 overflow-hidden">
                        <!-- Ruta local a la carpeta img -->
                        <img src="img/noticia-libros.jpg" alt="Libros y Publicaciones" class="w-full h-full object-cover">
                    </div>
                    <div class="p-6">
                        <span class="text-blue-600 text-xs font-bold uppercase tracking-wider">Publicaciones</span>
                        <h3 class="text-xl font-bold my-2 text-blue-900">Prospectiva y Desarrollo Territorial</h3>
                        <p class="text-slate-600 text-sm mb-4">Nuestras últimas producciones editoriales y papers disponibles para estudiantes y profesionales del sector.</p>
                        <a href="https://wa.me/5492954316211" class="text-blue-600 font-bold text-sm">Conseguir material</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer / Contacto -->
    <footer id="contacto" class="bg-slate-900 text-white pt-20 pb-10 px-4">
        <div class="max-w-7xl mx-auto">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 mb-16">
                <div>
                    <!-- Ruta local a la carpeta img para el logo en footer -->
                    <img src="img/image_ac78f4.jpg" alt="Logo Consultora Trama Territorios" class="h-20 mb-6 w-auto">
                    <p class="text-slate-400 mb-8 max-w-md">
                        Transformando el territorio a través de la educación y la economía social.
                    </p>
                    <div class="space-y-4 text-slate-300">
                        <div class="flex items-center gap-4">
                            <i class="fa-solid fa-phone text-blue-400 w-5"></i>
                            <span>+54 9 2954 31-6211</span>
                        </div>
                        <div class="flex items-center gap-4">
                            <i class="fa-solid fa-envelope text-blue-400 w-5"></i>
                            <!-- Correo actualizado -->
                            <span>formacionprofesional354@gmail.com</span>
                        </div>
                    </div>
                </div>
                <div>
                    <h3 class="text-xl font-bold mb-6">Contactanos directamente</h3>
                    <a href="https://wa.me/5492954316211?text=Hola,%20me%20encantar%C3%ADa%20recibir%20mas%20asesoramiento%20sobre%20Trama%20Territorios!%20Muchas%20Gracias." target="_blank" class="inline-block bg-green-600 hover:bg-green-700 text-white font-bold py-4 px-10 rounded-xl transition w-full text-center">
                        <i class="fa-brands fa-whatsapp mr-2"></i> Enviar WhatsApp
                    </a>
                </div>
            </div>
            
            <div class="border-t border-slate-800 pt-8 flex flex-col md:flex-row justify-between items-center gap-4">
                <div class="flex gap-6 text-2xl">
                    <a href="https://www.instagram.com/trama_territorios/" target="_blank" class="text-slate-500 hover:text-pink-500 transition"><i class="fa-brands fa-instagram"></i></a>
                    <a href="https://www.linkedin.com/in/gladys-cruse%C3%B1o-b41779337/" target="_blank" class="text-slate-500 hover:text-blue-500 transition"><i class="fa-brands fa-linkedin"></i></a>
                </div>
                <p class="text-slate-500 text-sm">© 2024 Consultora Trama Territorios.</p>
            </div>
        </div>
    </footer>

    <!-- WhatsApp Floating Button -->
    <a href="https://wa.me/5492954316211?text=Hola,%20me%20encantar%C3%ADa%20recibir%20mas%20asesoramiento%20sobre%20Trama%20Territorios!%20Muchas%20Gracias." class="whatsapp-float" target="_blank" title="Contactanos por WhatsApp">
        <i class="fa-brands fa-whatsapp"></i>
    </a>

    <script>
        const btn = document.getElementById('mobile-menu-button');
        const menu = document.getElementById('mobile-menu');

        btn.addEventListener('click', () => {
            menu.classList.toggle('hidden');
        });

        document.querySelectorAll('#mobile-menu a').forEach(link => {
            link.addEventListener('click', () => {
                menu.classList.add('hidden');
            });
        });
    </script>
</body>
</html>
