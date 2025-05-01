- 👋 Hi, I’m @edy93274
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
edy93274/edy93274 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="ro">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Full Deal</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    .fade-in {
      animation: fadeIn 2s ease-in forwards;
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    #intro {
      position: fixed;
      width: 100vw;
      height: 100vh;
      background: black;
      display: flex;
      justify-content: center;
      align-items: center;
      z-index: 50;
    }
    #intro h1 {
      color: white;
      font-size: 4rem;
      opacity: 0;
    }
  </style>
</head>
<body class="bg-gray-100 font-sans">
  <!-- Cinematic Intro -->
  <div id="intro">
    <h1 id="welcome" class="fade-in">Welcome</h1>
  </div>

  <!-- Main Content -->
  <div id="main" class="hidden">
    <!-- Hero Section -->
    <section class="text-center py-10 bg-white shadow">
      <h2 class="text-4xl font-bold mb-2">Full Deal</h2>
      <p class="text-gray-600">Oferte de nerefuzat. Comandă rapid pe WhatsApp!</p>
    </section>

    <!-- Produse -->
    <section class="py-10 px-4 grid grid-cols-1 md:grid-cols-3 gap-8 max-w-6xl mx-auto">
      <!-- Produs 1 -->
      <div class="bg-white shadow rounded-xl p-4">
        <img src="https://via.placeholder.com/300x200.png?text=Ceas+Inteligent" alt="Ceas" class="rounded mb-4">
        <h3 class="text-xl font-semibold mb-2">Ceas inteligent sport</h3>
        <p class="text-gray-600 mb-2">Monitorizare puls, pași și notificări.</p>
        <p class="font-bold text-lg mb-4">149 RON</p>
        <a href="https://wa.me/40767756065?text=Salut!%20Vreau%20sa%20comand%20Ceasul%20inteligent%20sport." target="_blank" class="bg-green-500 text-white px-4 py-2 rounded hover:bg-green-600">Comandă pe WhatsApp</a>
      </div>

      <!-- Produs 2 -->
      <div class="bg-white shadow rounded-xl p-4">
        <img src="https://via.placeholder.com/300x200.png?text=Lampa+LED" alt="Lampă LED" class="rounded mb-4">
        <h3 class="text-xl font-semibold mb-2">Lampă LED tactilă</h3>
        <p class="text-gray-600 mb-2">Perfectă pentru nopți liniștite.</p>
        <p class="font-bold text-lg mb-4">89 RON</p>
        <a href="https://wa.me/40767756065?text=Salut!%20Vreau%20sa%20comand%20Lampa%20LED%20tactila." target="_blank" class="bg-green-500 text-white px-4 py-2 rounded hover:bg-green-600">Comandă pe WhatsApp</a>
      </div>

      <!-- Produs 3 -->
      <div class="bg-white shadow rounded-xl p-4">
        <img src="https://via.placeholder.com/300x200.png?text=Casti+Wireless" alt="Căști" class="rounded mb-4">
        <h3 class="text-xl font-semibold mb-2">Căști wireless tip AirPods</h3>
        <p class="text-gray-600 mb-2">Sunet clar, conectare rapidă.</p>
        <p class="font-bold text-lg mb-4">119 RON</p>
        <a href="https://wa.me/40767756065?text=Salut!%20Vreau%20sa%20comand%20Castile%20wireless." target="_blank" class="bg-green-500 text-white px-4 py-2 rounded hover:bg-green-600">Comandă pe WhatsApp</a>
      </div>
    </section>

    <!-- Despre noi -->
    <section class="py-10 bg-gray-200 text-center px-4">
      <h3 class="text-2xl font-bold mb-4">Despre Full Deal</h3>
      <p class="text-gray-700 max-w-3xl mx-auto">Suntem un brand dedicat aducerii celor mai tari oferte direct în fața ta. Selectăm produse utile, moderne și cu preț corect, iar comanda se face rapid prin WhatsApp.</p>
    </section>

    <!-- Footer -->
    <footer class="text-center py-6 bg-white text-gray-500">
      &copy; 2025 Full Deal. Toate drepturile rezervate.
    </footer>
  </div>

  <script>
    // Intro timeout + show main content
    window.addEventListener('load', () => {
      setTimeout(() => {
        document.getElementById('intro').style.display = 'none';
        document.getElementById('main').classList.remove('hidden');
      }, 2500);
    });
  </script>
</body>
</html>

