<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bienvenidos a N.U.L.L</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .animate-fade-in {
            animation: fadeIn 0.8s ease-out forwards;
        }

        .neon-border {
            box-shadow: 0 0 15px rgba(139, 92, 246, 0.5), inset 0 0 15px rgba(139, 92, 246, 0.2);
        }
        
        .glitch-hover:hover {
            text-shadow: 2px 2px 0px #ff00c8, -2px -2px 0px #00fff2;
            transition: all 0.2s ease-in-out;
        }
    </style>
</head>
<body class="bg-gradient-to-br from-gray-900 via-gray-950 to-black min-h-screen text-gray-200 flex items-center justify-center p-4 sm:p-8">

    <main class="max-w-4xl w-full bg-gray-800/40 backdrop-blur-lg border border-gray-700/50 rounded-2xl p-6 sm:p-10 shadow-2xl animate-fade-in neon-border">
        
        <header class="text-center mb-10">
            <h1 class="text-4xl sm:text-6xl font-extrabold tracking-tight mb-2 text-transparent bg-clip-text bg-gradient-to-r from-purple-500 via-fuchsia-400 to-cyan-400 glitch-hover cursor-default">
                Bienvenidos a N.U.L.L
            </h1>
            <div class="h-1 w-24 bg-gradient-to-r from-purple-500 to-cyan-400 mx-auto rounded-full mt-4"></div>
        </header>

        <div class="flex justify-center mb-10 overflow-hidden rounded-xl">
            <!-- Usando Placehold.co para una imagen temática oscura con texto -->
            <img 
                src="https://placehold.co/800x400/111827/a855f7?text=N.U.L.L+Project\nRoleplay+Community&font=Montserrat" 
                alt="N.U.L.L Community Banner" 
                class="w-full max-w-3xl object-cover rounded-xl shadow-lg border-2 border-purple-500/30 transition-transform duration-500 hover:scale-105"
            >
        </div>

        <article class="space-y-6 text-lg sm:text-xl leading-relaxed text-gray-300 max-w-3xl mx-auto px-2">
            
            <p class="bg-gray-900/50 p-5 rounded-lg border-l-4 border-purple-500 shadow-inner">
                <span class="font-bold text-white">Hola, soy Mr.Null</span> también conocido como <span class="text-cyan-400 font-semibold">Mr.A</span> en roleplay. Aquí podrás visualizar mis proyectos y cualquier avance interesante.
            </p>

            <p class="bg-gray-900/50 p-5 rounded-lg border-l-4 border-cyan-400 shadow-inner">
                Si tienes interés o estás buscando una comunidad puedes unirte a <span class="font-bold text-purple-400">N.U.L.L</span> que es una comunidad dedicada al roleplay y tratamos de buscar nuevos miembros. El juego enfocado por el momento es para <span class="text-pink-400 font-semibold">ponytown</span>, si hay oportunidad o la comunidad crece podemos emigrar a otros juegos.
            </p>
            
        </article>

        <div class="mt-12 flex justify-center pb-4">
            <button class="px-8 py-3 bg-gradient-to-r from-purple-600 to-blue-600 hover:from-purple-500 hover:to-blue-500 text-white font-bold rounded-full shadow-lg shadow-purple-500/30 transition-all duration-300 transform hover:-translate-y-1 hover:shadow-purple-500/50 focus:outline-none focus:ring-2 focus:ring-purple-400 focus:ring-offset-2 focus:ring-offset-gray-900">
                Únete a la Comunidad
            </button>
        </div>

    </main>

</body>
</html>
