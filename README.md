<!doctype html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hops Food &amp; Drinks - Menú</title>
  <script src="https://cdn.tailwindcss.com/3.4.17"></script>
  <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;700&amp;family=Permanent+Marker&amp;display=swap" rel="stylesheet">
  <style>
    body { font-family: 'DM Sans', sans-serif; }
    .neon-title { font-family: 'Permanent Marker', cursive; }
    .perspective-grid {
      background-color: #0a0a12;
      background-image:
        linear-gradient(rgba(180,77,255,0.07) 1px, transparent 1px),
        linear-gradient(90deg, rgba(180,77,255,0.07) 1px, transparent 1px);
      background-size: 50px 50px;
    }
    .perspective-grid::before {
      content: '';
      position: fixed;
      bottom: 0; left: 0; right: 0;
      height: 40vh;
      background: linear-gradient(to top, rgba(180,77,255,0.08), transparent);
      pointer-events: none;
      z-index: 0;
    }
    .cat-plate {
      background: linear-gradient(135deg, #00e5ff, #b44dff);
      padding: 4px 16px;
      display: inline-block;
      clip-path: polygon(4% 0%, 100% 0%, 96% 100%, 0% 100%);
    }
    .menu-item { border-bottom: 1px solid rgba(255,255,255,0.06); }
    .menu-item:last-child { border-bottom: none; }
    nav::-webkit-scrollbar { display: none; }
    .category-btn { transition: all 0.2s; }
    .category-btn.active, .category-btn:hover { background: #00e5ff22; border-color: #00e5ff; color: #00e5ff; }
    .section-block { position: relative; z-index: 1; }
  </style>
</head>
<body class="min-h-screen perspective-grid text-white">
  
  <header class="text-center py-8 px-4 relative z-10">
    <p class="text-sm uppercase tracking-widest mb-2 text-cyan-400">Bienvenidos a</p>
    <h1 class="neon-title text-5xl mb-1 text-cyan-300" style="text-shadow: 0 0 12px #00e5ff88;">HOPS</h1>
    <p class="text-lg text-gray-300">Food &amp; Drinks</p>
  </header>

  <nav id="cat-nav" class="sticky top-0 z-50 bg-[#0a0a12]/95 backdrop-blur px-4 py-3 flex gap-2 overflow-x-auto border-b border-cyan-900/30">
    <button class="category-btn flex-shrink-0 px-3 py-1.5 rounded-full border border-gray-600 text-gray-400 text-xs font-medium whitespace-nowrap" onclick="document.getElementById('sec-0').scrollIntoView({behavior:'smooth',block:'start'})">Tragos y Cócteles</button>
    <button class="category-btn flex-shrink-0 px-3 py-1.5 rounded-full border border-gray-600 text-gray-400 text-xs font-medium whitespace-nowrap" onclick="document.getElementById('sec-1').scrollIntoView({behavior:'smooth',block:'start'})">Autoría Hops</button>
    <button class="category-btn flex-shrink-0 px-3 py-1.5 rounded-full border border-gray-600 text-gray-400 text-xs font-medium whitespace-nowrap" onclick="document.getElementById('sec-6').scrollIntoView({behavior:'smooth',block:'start'})">Burgers</button>
  </nav>

  <main class="max-w-6xl mx-auto px-4 py-6 relative z-10">
    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">

      <!-- Tragos y Cócteles -->
      <div id="sec-0" class="section-block scroll-mt-16 mb-2">
        <div class="mb-3">
          <span class="cat-plate">
            <span class="text-white uppercase text-sm tracking-wide font-bold" style="font-family:'Permanent Marker',cursive">Tragos y Cócteles</span>
          </span>
        </div>
        
        <div class="menu-item flex justify-between items-baseline py-2 gap-3">
          <div class="min-w-0">
            <span class="text-gray-200 text-sm uppercase font-medium">Fernet Branca</span>
            <span class="block text-gray-400 text-xs">Con Coca-Cola y hielo</span>
          </div>
          <span class="text-cyan-300 text-sm font-medium whitespace-nowrap">$4.500</span>
        </div>

        <div class="menu-item flex justify-between items-baseline py-2 gap-3">
          <div class="min-w-0">
            <span class="text-gray-200 text-sm uppercase font-medium">Gin Tonic Clásico</span>
            <span class="block text-gray-400 text-xs">Gin, agua tónica y rodaja de pepino/limón</span>
          </div>
          <span class="text-cyan-300 text-sm font-medium whitespace-nowrap">$5.000</span>
        </div>
      </div>

      <!-- Burgers -->
      <div id="sec-6" class="section-block scroll-mt-16 mb-2">
        <div class="mb-3">
          <span class="cat-plate">
            <span class="text-white uppercase text-sm tracking-wide font-bold" style="font-family:'Permanent Marker',cursive">Burgers</span>
          </span>
        </div>

        <div class="menu-item flex justify-between items-baseline py-2 gap-3">
          <div class="min-w-0">
            <span class="text-gray-200 text-sm uppercase font-medium">Cheeseburger</span>
            <span class="block text-gray-400 text-xs">Doble medallón, quíntuple cheddar y salsa de la casa</span>
          </div>
          <span class="text-cyan-300 text-sm font-medium whitespace-nowrap">$8.500</span>
        </div>
      </div>

    </div>
  </main>

</body>
</html>
