<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>One For All - Apps</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-900 text-white">
  <!-- Encabezado con logo -->
  <header class="bg-gray-800 py-4">
    <div class="container mx-auto flex items-center justify-between px-4">
      <div class="flex items-center">
        <!-- Enlace actual; reemplaza con el nuevo Direct Link tras quitar el fondo -->
        <img src="https://i.ibb.co/tpFRs44R/A-F-O.png" alt="Logo de One For All" class="h-12 mr-4">
        <h1 class="text-yellow-400">One For All</h1>
      </div>
      <nav>
        <ul class="flex space-x-4">
          <li><a href="#apps" class="text-yellow-400 hover:underline">Apps</a></li>
          <li><a href="#contacto" class="text-yellow-400 hover:underline">Contacto</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Sección de apps -->
  <section id="apps" class="py-12">
    <div class="container mx-auto px-4">
      <h2 class="text-yellow-400 text-3xl mb-8 text-center">Nuestras Aplicaciones</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <!-- App 1 -->
        <div class="bg-gray-800 p-6 rounded-lg shadow-lg">
          <h3 class="text-yellow-400 text-xl mb-2">App 1</h3>
          <p class="text-white mb-4">Descripción de tu primera app. Explica qué hace y por qué es útil.</p>
          <a href="#" class="text-yellow-400 hover:underline">Descargar o Ver Más</a>
        </div>
        <!-- App 2 -->
        <div class="bg-gray-800 p-6 rounded-lg shadow-lg">
          <h3 class="text-yellow-400 text-xl mb-2">App 2</h3>
          <p class="text-white mb-4">Descripción de tu segunda app. Añade detalles atractivos.</p>
          <a href="#" class="text-yellow-400 hover:underline">Descargar o Ver Más</a>
        </div>
        <!-- Añade más apps aquí -->
      </div>
    </div>
  </section>

  <!-- Pie de página -->
  <footer id="contacto" class="bg-gray-700 py-6">
    <div class="container mx-auto px-4 text-center">
      <p>© 2025 One For All. Todos los derechos reservados.</p>
      <p class="mt-2">Contacto: <a href="mailto:tuemail@example.com" class="text-yellow-400 hover:underline">tuemail@example.com</a></p>
    </div>
  </footer>
</body>
</html>
