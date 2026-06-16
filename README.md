<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gracie Academy | Jiu-Jitsu Brasileño</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
    <style>
        .hero-bg {
            background-image: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://picsum.photos/id/1015/1920/1080');
            background-size: cover;
            background-position: center;
        }
        .section-bg {
            background-color: #0f172a;
        }
        .nav-link {
            transition: all 0.3s;
        }
        .nav-link:hover {
            color: #eab308;
            transform: translateY(-2px);
        }
        .card-hover:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 25px -5px rgb(0 0 0 / 0.1), 0 8px 10px -6px rgb(0 0 0 / 0.1);
        }
    </style>
</head>
<body class="bg-zinc-950 text-white font-sans">

    <!-- NAV -->
    <nav class="bg-black border-b border-yellow-600 fixed w-full z-50">
        <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
            <div class="flex items-center gap-3">
                <i class="fa-solid fa-fist-raised text-3xl text-yellow-500"></i>
                <div>
                    <h1 class="text-2xl font-bold tracking-tighter">GRACIE ACADEMY</h1>
                    <p class="text-xs text-yellow-500 -mt-1">Jiu-Jitsu Brasileño</p>
                </div>
            </div>
            <div class="hidden md:flex gap-8 text-sm font-medium">
                <a href="#inicio" class="nav-link">INICIO</a>
                <a href="#sobre" class="nav-link">SOBRE JIUJITSU</a>
                <a href="#historia" class="nav-link">HISTORIA</a>
                <a href="#beneficios" class="nav-link">BENEFICIOS</a>
                <a href="#tecnicas" class="nav-link">TÉCNICAS</a>
                <a href="#galeria" class="nav-link">GALERÍA</a>
                <a href="#instructores" class="nav-link">INSTRUCTORES</a>
                <a href="#contacto" class="nav-link">CONTACTO</a>
            </div>
            <button onclick="document.getElementById('contacto').scrollIntoView({behavior: 'smooth'})"
                    class="bg-yellow-500 hover:bg-yellow-600 text-black font-bold px-6 py-2 rounded-lg transition">
                ÚNETE AHORA
            </button>
        </div>
    </nav>

    <!-- HERO -->
    <section id="inicio" class="hero-bg h-screen flex items-center justify-center text-center pt-16">
        <div class="max-w-4xl mx-auto px-6">
            <h2 class="text-6xl md:text-7xl font-black tracking-tighter mb-4">JIU-JITSU BRASILEÑO</h2>
            <p class="text-2xl md:text-3xl text-yellow-400 mb-8">El arte marcial más efectivo del mundo</p>
            <p class="text-xl max-w-2xl mx-auto mb-10">Domina tu cuerpo, tu mente y tu espíritu. Entrena con los mejores.</p>
            <div class="flex gap-4 justify-center">
                <button onclick="document.getElementById('contacto').scrollIntoView({behavior: 'smooth'})"
                        class="bg-yellow-500 text-black px-10 py-4 rounded-xl font-bold text-lg hover:bg-yellow-400 transition">
                    COMENZAR ENTRENAMIENTO
                </button>
                <button onclick="document.getElementById('galeria').scrollIntoView({behavior: 'smooth'})"
                        class="border border-white hover:bg-white hover:text-black px-10 py-4 rounded-xl font-bold text-lg transition">
                    VER GALERÍA
                </button>
            </div>
        </div>
    </section>

    <!-- SOBRE JIUJITSU -->
    <section id="sobre" class="section-bg py-20">
        <div class="max-w-7xl mx-auto px-6">
            <h2 class="text-5xl font-bold text-center mb-16">¿Qué es el Jiu-Jitsu Brasileño?</h2>
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div>
                    <p class="text-lg leading-relaxed mb-6">
                        El Jiu-Jitsu Brasileño (BJJ) es un arte marcial y sistema de combate cuerpo a cuerpo basado principalmente en el control de la posición y las técnicas de sumisión. Fue desarrollado por los hermanos Gracie en Brasil a partir del Judo y Jiu-Jitsu japonés tradicional.
                    </p>
                    <p class="text-lg leading-relaxed mb-6">
                        A diferencia de muchas otras artes marciales, el BJJ se enfoca en la pelea en el suelo, donde un practicante más pequeño y débil puede derrotar a un oponente más grande y fuerte mediante el uso de palancas, estrangulamientos y control posicional.
                    </p>
                    <ul class="space-y-4 text-lg">
                        <li class="flex gap-3"><i class="fa-solid fa-check text-yellow-500 mt-1"></i> Énfasis en la lucha en suelo</li>
                        <li class="flex gap-3"><i class="fa-solid fa-check text-yellow-500 mt-1"></i> Técnicas de sumisión (llaves y estrangulamientos)</li>
                        <li class="flex gap-3"><i class="fa-solid fa-check text-yellow-500 mt-1"></i> Desarrollo de fuerza funcional y resistencia</li>
                        <li class="flex gap-3"><i class="fa-solid fa-check text-yellow-500 mt-1"></i> Mejora de la disciplina mental</li>
                    </ul>
                </div>
                <div class="rounded-2xl overflow-hidden shadow-2xl">
                    <img src="https://picsum.photos/id/201/800/600" alt="Jiu-Jitsu en acción" class="w-full h-full object-cover">
                </div>
            </div>
        </div>
    </section>

    <!-- HISTORIA -->
    <section id="historia" class="py-20 bg-black">
        <div class="max-w-7xl mx-auto px-6">
            <h2 class="text-5xl font-bold text-center mb-16">Nuestra Historia</h2>
            <div class="max-w-3xl mx-auto space-y-10">
                <div class="flex gap-8">
                    <div class="w-24 h-24 bg-yellow-500 text-black rounded-full flex-shrink-0 flex items-center justify-center text-4xl font-bold">1920</div>
                    <div>
                        <h3 class="text-2xl font-semibold mb-2">Orígenes en Japón</h3>
                        <p class="text-zinc-400">Mitsuyo Maeda, experto en Jiu-Jitsu japonés, viaja a Brasil y enseña sus técnicas a Carlos Gracie.</p>
                    </div>
                </div>
                <div class="flex gap-8">
                    <div class="w-24 h-24 bg-yellow-500 text-black rounded-full flex-shrink-0 flex items-center justify-center text-4xl font-bold">1930</div>
                    <div>
                        <h3 class="text-2xl font-semibold mb-2">Nacimiento del BJJ</h3>
                        <p class="text-zinc-400">Los hermanos Gracie perfeccionan el arte y lo adaptan a la realidad de las peleas callejeras.</p>
                    </div>
                </div>
                <div class="flex gap-8">
                    <div class="w-24 h-24 bg-yellow-500 text-black rounded-full flex-shrink-0 flex items-center justify-center text-4xl font-bold">1993</div>
                    <div>
                        <h3 class="text-2xl font-semibold mb-2">UFC y Explosión Mundial</h3>
                        <p class="text-zinc-400">Royce Gracie gana los primeros torneos de UFC, demostrando la superioridad del Jiu-Jitsu Brasileño.</p>
                    </div>
                </div>
                <div class="flex gap-8">
                    <div class="w-24 h-24 bg-yellow-500 text-black rounded-full flex-shrink-0 flex items-center justify-center text-4xl font-bold">HOY</div>
                    <div>
                        <h3 class="text-2xl font-semibold mb-2">Deporte Global</h3>
                        <p class="text-zinc-400">Millones de practicantes en todo el mundo. El BJJ es disciplina olímpica en desarrollo y base de las MMA modernas.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- BENEFICIOS -->
    <section id="beneficios" class="section-bg py-20">
        <div class="max-w-7xl mx-auto px-6">
            <h2 class="text-5xl font-bold text-center mb-16">Beneficios del Jiu-Jitsu</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-zinc-900 p-8 rounded-3xl card-hover">
                    <i class="fa-solid fa-dumbbell text-5xl text-yellow-500 mb-6"></i>
                    <h3 class="text-2xl font-bold mb-4">Físicos</h3>
                    <ul class="space-y-3 text-zinc-300">
                        <li>• Aumento de fuerza y resistencia</li>
                        <li>• Mejora de la coordinación</li>
                        <li>• Pérdida de grasa y ganancia muscular</li>
                        <li>• Mayor flexibilidad</li>
                    </ul>
                </div>
                <div class="bg-zinc-900 p-8 rounded-3xl card-hover">
                    <i class="fa-solid fa-brain text-5xl text-yellow-500 mb-6"></i>
                    <h3 class="text-2xl font-bold mb-4">Mentales</h3>
                    <ul class="space-y-3 text-zinc-300">
                        <li>• Mayor disciplina y enfoque</li>
                        <li>• Reducción de estrés y ansiedad</li>
                        <li>• Desarrollo de confianza</li>
                        <li>• Mejora de la resiliencia</li>
                    </ul>
                </div>
                <div class="bg-zinc-900 p-8 rounded-3xl card-hover">
                    <i class="fa-solid fa-users text-5xl text-yellow-500 mb-6"></i>
                    <h3 class="text-2xl font-bold mb-4">Personales</h3>
                    <ul class="space-y-3 text-zinc-300">
                        <li>• Autodefensa efectiva</li>
                        <li>• Comunidad fuerte y solidaria</li>
                        <li>• Superación personal constante</li>
                        <li>• Valores de respeto y humildad</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- TÉCNICAS -->
    <section id="tecnicas" class="py-20 bg-black">
        <div class="max-w-7xl mx-auto px-6">
            <h2 class="text-5xl font-bold text-center mb-16">Técnicas Principales</h2>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-zinc-900 rounded-3xl overflow-hidden card-hover">
                    <img src="https://picsum.photos/id/237/600/400" class="w-full h-56 object-cover" alt="Guardia">
                    <div class="p-6">
                        <h3 class="text-2xl font-bold mb-2">La Guardia</h3>
                        <p class="text-zinc-400">Posición fundamental donde controlas al oponente con las piernas desde abajo.</p>
                    </div>
                </div>
                <div class="bg-zinc-900 rounded-3xl overflow-hidden card-hover">
                    <img src="https://picsum.photos/id/866/600/400" class="w-full h-56 object-cover" alt="Montada">
                    <div class="p-6">
                        <h3 class="text-2xl font-bold mb-2">Montada</h3>
                        <p class="text-zinc-400">Posición dominante de control total sobre el oponente.</p>
                    </div>
                </div>
                <div class="bg-zinc-900 rounded-3xl overflow-hidden card-hover">
                    <img src="https://picsum.photos/id/1015/600/400" class="w-full h-56 object-cover" alt="Triángulo">
                    <div class="p-6">
                        <h3 class="text-2xl font-bold mb-2">Triángulo</h3>
                        <p class="text-zinc-400">Una de las sumisiones más icónicas del BJJ.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- GALERÍA (donde el usuario puede elegir fotos) -->
    <section id="galeria" class="section-bg py-20">
        <div class="max-w-7xl mx-auto px-6">
            <h2 class="text-5xl font-bold text-center mb-16">Galería de Entrenamiento</h2>
            <p class="text-center text-zinc-400 mb-12">Reemplaza las URLs de las imágenes con las fotos que tú elijas (sube tus imágenes a un hosting gratuito como ImgBB, Postimages o usa enlaces directos).</p>
            
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
                <!-- Imagen 1 -->
                <div class="group relative overflow-hidden rounded-3xl">
                    <img src="https://picsum.photos/id/1015/600/600" 
                         onclick="this.src=prompt('Pega la nueva URL de la imagen:') || this.src"
                         class="w-full h-80 object-cover transition-transform group-hover:scale-110 cursor-pointer" 
                         alt="Entrenamiento Jiu-Jitsu">
                    <div class="absolute bottom-0 left-0 right-0 bg-gradient-to-t from-black p-4">
                        <p class="text-sm">Rodando en el tatami</p>
                    </div>
                </div>

                <!-- Imagen 2 -->
                <div class="group relative overflow-hidden rounded-3xl">
                    <img src="https://picsum.photos/id/201/600/600" 
                         onclick="this.src=prompt('Pega la nueva URL de la imagen:') || this.src"
                         class="w-full h-80 object-cover transition-transform group-hover:scale-110 cursor-pointer" 
                         alt="Clase de Jiu-Jitsu">
                </div>

                <!-- Imagen 3 -->
                <div class="group relative overflow-hidden rounded-3xl">
                    <img src="https://picsum.photos/id/866/600/600" 
                         onclick="this.src=prompt('Pega la nueva URL de la imagen:') || this.src"
                         class="w-full h-80 object-cover transition-transform group-hover:scale-110 cursor-pointer" 
                         alt="Competición">
                </div>

                <!-- Imagen 4 -->
                <div class="group relative overflow-hidden rounded-3xl">
                    <img src="https://picsum.photos/id/237/600/600" 
                         onclick="this.src=prompt('Pega la nueva URL de la imagen:') || this.src"
                         class="w-full h-80 object-cover transition-transform group-hover:scale-110 cursor-pointer" 
                         alt="Técnica de sumisión">
                </div>
            </div>
            
            <div class="text-center mt-12">
                <p class="text-yellow-400 text-sm">Haz clic en cualquier imagen para cambiarla por la que tú prefieras.</p>
            </div>
        </div>
    </section>

    <!-- INSTRUCTORES -->
    <section id="instructores" class="py-20 bg-black">
        <div class="max-w-7xl mx-auto px-6">
            <h2 class="text-5xl font-bold text-center mb-16">Nuestros Instructores</h2>
            <div class="grid md:grid-cols-3 gap-10">
                <div class="text-center">
                    <img src="https://picsum.photos/id/64/400/400" class="w-48 h-48 mx-auto rounded-2xl object-cover mb-6" alt="Instructor">
                    <h3 class="text-2xl font-bold">Prof. Carlos Mendes</h3>
                    <p class="text-yellow-500">Cinta Negra 4° Grado</p>
                    <p class="mt-3 text-sm text-zinc-400">Más de 20 años de experiencia. Campeón Panamericano.</p>
                </div>
                <div class="text-center">
                    <img src="https://picsum.photos/id/1005/400/400" class="w-48 h-48 mx-auto rounded-2xl object-cover mb-6" alt="Instructor">
                    <h3 class="text-2xl font-bold">Prof. Ana Silva</h3>
                    <p class="text-yellow-500">Cinta Negra</p>
                    <p class="mt-3 text-sm text-zinc-400">Especialista en Jiu-Jitsu femenino y defensa personal.</p>
                </div>
                <div class="text-center">
                    <img src="https://picsum.photos/id/883/400/400" class="w-48 h-48 mx-auto rounded-2xl object-cover mb-6" alt="Instructor">
                    <h3 class="text-2xl font-bold">Prof. Lucas Ferreira</h3>
                    <p class="text-yellow-500">Cinta Negra 2° Grado</p>
                    <p class="mt-3 text-sm text-zinc-400">Competidor profesional de MMA y BJJ.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- TESTIMONIOS -->
    <section class="section-bg py-20">
        <div class="max-w-4xl mx-auto px-6 text-center">
            <h2 class="text-5xl font-bold mb-12">Lo que dicen nuestros alumnos</h2>
            <div class="italic text-xl">"El Jiu-Jitsu cambió mi vida. No solo físicamente, sino en confianza y disciplina. Es la mejor decisión que he tomado."</div>
            <p class="mt-6 text-yellow-400">- María González, 8 meses entrenando</p>
        </div>
    </section>

    <!-- CONTACTO -->
    <section id="contacto" class="py-20 bg-black">
        <div class="max-w-4xl mx-auto px-6">
            <h2 class="text-5xl font-bold text-center mb-12">¿Listo para empezar?</h2>
            <div class="bg-zinc-900 p-10 rounded-3xl">
                <form class="space-y-6">
                    <div class="grid md:grid-cols-2 gap-6">
                        <input type="text" placeholder="Nombre completo" 
                               class="bg-zinc-800 border border-zinc-700 rounded-xl px-6 py-4 focus:outline-none focus:border-yellow-500">
                        <input type="email" placeholder="Correo electrónico" 
                               class="bg-zinc-800 border border-zinc-700 rounded-xl px-6 py-4 focus:outline-none focus:border-yellow-500">
                    </div>
                    <input type="tel" placeholder="Teléfono" 
                           class="w-full bg-zinc-800 border border-zinc-700 rounded-xl px-6 py-4 focus:outline-none focus:border-yellow-500">
                    <textarea placeholder="¿Qué te gustaría saber o qué horario prefieres?" rows="5"
                              class="w-full bg-zinc-800 border border-zinc-700 rounded-xl px-6 py-4 focus:outline-none focus:border-yellow-500"></textarea>
                    <button type="button" 
                            class="w-full bg-yellow-500 hover:bg-yellow-400 text-black font-bold py-5 rounded-2xl text-lg transition">
                        ENVIAR MENSAJE
                    </button>
                </form>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="bg-black py-12 border-t border-zinc-800">
        <div class="max-w-7xl mx-auto px-6 text-center">
            <p class="text-zinc-500">&copy; 2026 Gracie Academy - Jiu-Jitsu Brasileño</p>
            <p class="text-xs text-zinc-600 mt-4">Creado como ejemplo para ti. Puedes copiar todo este código y modificarlo libremente.</p>
        </div>
    </footer>

    <script>
        // Tailwind script ya cargado
        console.log("%cPágina de Jiu-Jitsu cargada correctamente. ¡Osu!", "color: #eab308; font-size: 14px");
    </script>
</body>
</html>
