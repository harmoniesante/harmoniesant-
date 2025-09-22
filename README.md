<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Harmonie Santé Pour Tous</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="font-sans text-gray-800">

  <!-- Header -->
  <header class="bg-gradient-to-r from-green-600 to-red-600 text-white p-4 sticky top-0 z-50">
    <div class="max-w-screen-xl mx-auto flex justify-between items-center">
      <h1 class="text-xl sm:text-2xl font-bold">Harmonie Santé Pour Tous</h1>
      
      <!-- Menu Desktop -->
      <nav class="hidden md:block" aria-label="Menu principal">
        <ul class="flex space-x-6">
          <li><a href="#about" class="hover:underline">À propos</a></li>
          <li><a href="#products" class="hover:underline">Produits</a></li>
          <li><a href="#blog" class="hover:underline">Blog</a></li>
          <li><a href="#testimonials" class="hover:underline">Témoignages</a></li>
          <li><a href="#contact" class="hover:underline">Contact</a></li>
        </ul>
      </nav>

      <!-- Bouton mobile -->
      <button id="menu-btn" class="md:hidden focus:outline-none">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-7" fill="none" 
             viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                d="M4 6h16M4 12h16M4 18h16" />
        </svg>
      </button>
    </div>

    <!-- Menu Mobile -->
    <nav id="mobile-menu" class="hidden md:hidden bg-green-700 text-white px-6 py-4">
      <ul class="flex flex-col space-y-3">
        <li><a href="#about">À propos</a></li>
        <li><a href="#products">Produits</a></li>
        <li><a href="#blog">Blog</a></li>
        <li><a href="#testimonials">Témoignages</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero -->
  <section class="bg-green-50 py-20 text-center">
    <h2 class="text-3xl sm:text-4xl font-extrabold text-green-700">
      Votre partenaire bien-être au naturel
    </h2>
    <p class="mt-4 text-lg max-w-2xl mx-auto px-4">
      Découvrez des solutions à base d’Aloe Vera pour une santé harmonieuse et durable.
    </p>
    <a href="#products" 
       class="mt-6 inline-block bg-red-600 text-white px-6 py-3 rounded-full shadow-lg hover:scale-105 hover:bg-red-700 transition">
      Je découvre les produits
    </a>
  </section>

  <!-- ... (le reste de tes sections reste identique, mais avec les mêmes ajustements de responsive et styles) ... -->

  <!-- Footer -->
  <footer class="bg-gradient-to-r from-green-600 to-red-600 text-white py-6 text-center">
    <p>&copy; 2025 Harmonie Santé Pour Tous. Tous droits réservés.</p>
  </footer>

  <!-- Script menu burger -->
  <script>
    const btn = document.getElementById('menu-btn');
    const menu = document.getElementById('mobile-menu');
    btn.addEventListener('click', () => {
      menu.classList.toggle('hidden');
    });
  </script>
</body>
</html>
