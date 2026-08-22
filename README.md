# Menu-Hops
Menu de hops
index.html
<html lang="es">
 <head><script>window["__codeletBootstrap__"]=JSON.parse('{"A":"A","B":"20260821-05-d0038b4","C":{"Abril Fatface":"YACgEZbkUVE,0","Alfa Slab One":"YACgEYS9sJU,0","Anton":"YACgEcYqQ-A,0","Archivo":"YAHO2-t-jNE,0","Arial":"YAGyDvJ_4Ts,0","Bebas Neue":"YACgESME5ew,0","Bricolage Grotesque":"YAFyMcdwzpc,0","Canva Sans":"YAFLd8sKbwc,2","Caveat":"YALBs2ploWQ,0","Comic Sans MS":"YAHO2VMiyZo,0","Cormorant Garamond":"YAFdJhX-538,0","Courier New":"YAGzXiGs0_8,0","DM Sans":"YAD1aU3sLnI,0","DM Serif Display":"YAD1aYG82rc,0","Forum":"YACgEcnnqB4,0","Fraunces":"YAEul-FRQw4,0","Georgia":"YAGzXkO0pEM,0","Helvetica Neue":"YAFcf6CtJfI,0","Impact":"YAFcfnjI7Vk,0","Inter":"YAFdJvSyp_k,3","Iowan Old Style":"YAGNIFa8j9o,0","Jacques Francois":"YAHO2a5g66Q,0","JetBrains Mono":"YAFdJksXcAk,0","Libre Baskerville":"YACgEUFdPdA,0","Manrope":"YAHO2b2feC4,0","Merriweather":"YACgEXvHxxs,0","Montserrat":"YADLjI9qxTA,0","Nunito":"YACgEX8C5Gg,0","Oleo Script":"YACgEQQ14jI,0","Phantom Sans":"YAHO2E8Pb88,0","Playfair Display":"YACgEYmuCJE,0","Poppins":"YAFdJjbTu24,1","Press Start 2P":"YAFyGr-8pmQ,0","Quicksand":"YADWjpfPmdk,0","Raleway":"YACgEVg3xZg,0","Segoe UI":"YAHNdRD1Klw,0","Source Sans 3":"YAG4lO1Mj10,0","Spectral":"YAHO2rVUHIM,0","Times New Roman":"YAGzXW3gftg,0","Times":"YAGzXW3gftg,0","Ubuntu":"YACgERDU--Q,0","Work Sans":"YAGXhLOKv44,0","Yellowtail":"YACgEYG4kG4,0","ui-monospace":"YADlN8CFZ8Q,0","ui-sans-serif":"YACkoN-xg4g,0"}}');</script><script src="/_sdk/50d846425a1e5082.telemetry_sdk.js" integrity="sha512-Otbex+ztlVbcEGql0rXGd/3E3ee/hqAntg6DeuUEMG6pIPbXGOSvZbFZVzknAXi1tH/itQ+ijEhOTr2aWj6CXg=="></script>
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
    .section-block img.canva-image { height: 220px !important; aspect-ratio: 4 / 3; object-fit: contain !important; object-position: center; background: #11131d; }
    #sec-9 { display: none; }
    .dessert-carousel { position: relative; overflow-x: auto; display: flex; gap: 10px; scroll-snap-type: x mandatory; scrollbar-width: none; -webkit-overflow-scrolling: touch; padding-bottom: 4px; }
    .dessert-carousel::-webkit-scrollbar { display: none; }
    .dessert-carousel img.canva-image { flex: 0 0 82%; scroll-snap-align: center; height: 250px !important; aspect-ratio: 4 / 3; }
    .carousel-hint { display: flex; align-items: center; justify-content: center; gap: 6px; color: #9ca3af; font-size: 11px; letter-spacing: .08em; text-transform: uppercase; margin-top: 6px; }
    .carousel-hint svg { width: 14px; height: 14px; color: #00e5ff; }
  </style>
  <script src="https://cdn.jsdelivr.net/npm/lucide@0.263.0/dist/umd/lucide.min.js" type="text/javascript"></script>
  <script src="/_sdk/b3bf9e8ac58e6ad6.data_sdk.js" type="text/javascript" integrity="sha512-otc1u9NYq9Ms5Jt//7vmhrrqR5CLPr8Jdgs6741gqniClfLMcfmC+jK/cKuQdhLv6G0esJ/FzaMS9tv0T/vj/Q=="></script>
  <script src="/_sdk/a27879be4562f807.resizing_sdk.js" type="text/javascript" integrity="sha512-trcxRwz+QLrzK0Dqg95xqVRryR7WtWui2YopXyzOIr3WMde3j/xCRgT63/b/EAg7klDsAOuHzoRgoryhwm8QFw=="></script>
 </head>
 <body data-template-id="__page-root" class="min-h-screen perspective-grid text-white">
  <header class="text-center py-8 px-4 relative z-10">
   <p data-template-id="welcome-text" class="canva-text text-sm uppercase tracking-widest mb-2"></p>
   <h1 data-template-id="brand-name" class="canva-text neon-title text-5xl mb-1" style="text-shadow: 0 0 12px #00e5ff88;"></h1>
   <p data-template-id="brand-sub" class="canva-text text-lg"></p>
  </header>
  <nav id="cat-nav" class="sticky top-0 z-50 bg-[#0a0a12]/95 backdrop-blur px-4 py-3 flex gap-2 overflow-x-auto border-b border-cyan-900/30"><button class="category-btn flex-shrink-0 px-3 py-1.5 rounded-full border border-gray-600 text-gray-400 text-xs font-medium whitespace-nowrap" onclick="document.getElementById('sec-0').scrollIntoView({behavior:'smooth',block:'start'})">Tragos y Cocteles</button> <button class="category-btn flex-shrink-0 px-3 py-1.5 rounded-full border border-gray-600 text-gray-400 text-xs font-medium whitespace-nowrap" onclick="document.getElementById('sec-1').scrollIntoView({behavior:'smooth',block:'start'})">Autoría Hops</button> <button class="category-btn flex-shrink-0 px-3 py-1.5 rounded-full border border-gray-600 text-gray-400 text-xs font-medium whitespace-nowrap" onclick="document.getElementById('sec-2').scrollIntoView({behavior:'smooth',block:'start'})">Espumantes</button> <button class="category-btn flex-shrink-0 px-3 py-1.5 rounded-full border border-gray-600 text-gray-400 text-xs font-medium whitespace-nowrap" onclick="document.getElementById('sec-3').scrollIntoView({behavior:'smooth',block:'start'})">Destilados</button> <button class="category-btn flex-shrink-0 px-3 py-1.5 rounded-full border border-gray-600 text-gray-400 text-xs font-medium whitespace-nowrap" onclick="document.getElementById('sec-4').scrollIntoView({behavior:'smooth',block:'start'})">Bebidas Sin Alcohol</button> <button class="category-btn flex-shrink-0 px-3 py-1.5 rounded-full border border-gray-600 text-gray-400 text-xs font-medium whitespace-nowrap" onclick="document.getElementById('sec-5').scrollIntoView({behavior:'smooth',block:'start'})">Entradas</button> <button class="category-btn flex-shrink-0 px-3 py-1.5 rounded-full border border-gray-600 text-gray-400 text-xs font-medium whitespace-nowrap" onclick="document.getElementById('sec-6').scrollIntoView({behavior:'smooth',block:'start'})">Burgers</button> <button class="category-btn flex-shrink-0 px-3 py-1.5 rounded-full border border-gray-600 text-gray-400 text-xs font-medium whitespace-nowrap" onclick="document.getElementById('sec-7').scrollIntoView({behavior:'smooth',block:'start'})">Extras</button> <button class="category-btn flex-shrink-0 px-3 py-1.5 rounded-full border border-gray-600 text-gray-400 text-xs font-medium whitespace-nowrap" onclick="document.getElementById('sec-8').scrollIntoView({behavior:'smooth',block:'start'})">Pizzas</button> <button class="category-btn flex-shrink-0 px-3 py-1.5 rounded-full border border-gray-600 text-gray-400 text-xs font-medium whitespace-nowrap" onclick="document.getElementById('sec-10').scrollIntoView({behavior:'smooth',block:'start'})">Milanesas</button> <button class="category-btn flex-shrink-0 px-3 py-1.5 rounded-full border border-gray-600 text-gray-400 text-xs font-medium whitespace-nowrap" onclick="document.getElementById('sec-11').scrollIntoView({behavior:'smooth',block:'start'})">Tacos</button> <button class="category-btn flex-shrink-0 px-3 py-1.5 rounded-full border border-gray-600 text-gray-400 text-xs font-medium whitespace-nowrap" onclick="document.getElementById('sec-12').scrollIntoView({behavior:'smooth',block:'start'})">Sándwiches</button> <button class="category-btn flex-shrink-0 px-3 py-1.5 rounded-full border border-gray-600 text-gray-400 text-xs font-medium whitespace-nowrap" onclick="document.getElementById('sec-13').scrollIntoView({behavior:'smooth',block:'start'})">Postres</button>
  </nav>
  <main class="max-w-6xl mx-auto px-4 py-6 relative z-10">
   <div class="grid grid-cols-1 md:grid-cols-2 gap-6"><!-- Tragos y Cocteles -->
    <div id="sec-0" class="section-block scroll-mt-16 mb-2"><img data-template-id="img-cat-0" class="canva-image w-full h-40 object-cover rounded-lg mb-3" loading="lazy">
     <div class="mb-3">
      <span class="cat-plate"><span data-template-id="cat-0" class="canva-text text-white uppercase text-sm tracking-wide" style="font-family:'Permanent Marker',cursive"></span></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t0-i0-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t0-i0-d" class="canva-text block text-gray-400 text-xs"></span>
      </div><span data-template-id="t0-i0-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t0-i1-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t0-i1-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t0-i2-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t0-i2-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t0-i3-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t0-i3-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t0-i4-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t0-i4-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t0-i5-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t0-i5-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t0-i6-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t0-i6-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t0-i7-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t0-i7-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t0-i8-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t0-i8-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t0-i9-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t0-i9-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t0-i10-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t0-i10-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
    </div><!-- Autoría Hops -->
    <div id="sec-1" class="section-block scroll-mt-16 mb-2 min-h-[220px]" style="display:block !important; visibility:visible !important; opacity:1 !important;"><img data-template-id="img-cat-1" class="canva-image w-full h-40 object-cover rounded-lg mb-3" loading="lazy">
     <div class="mb-3">
      <span class="cat-plate"><span data-template-id="cat-1" class="canva-text text-white uppercase text-sm tracking-wide" style="font-family:'Permanent Marker',cursive"></span></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t1-i0-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t1-i0-d" class="canva-text block text-gray-400 text-xs"></span>
      </div><span data-template-id="t1-i0-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t1-i1-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t1-i1-d" class="canva-text block text-gray-400 text-xs"></span>
      </div><span data-template-id="t1-i1-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t1-i2-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t1-i2-d" class="canva-text block text-gray-400 text-xs"></span>
      </div><span data-template-id="t1-i2-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t1-i3-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t1-i3-d" class="canva-text block text-gray-400 text-xs"></span>
      </div><span data-template-id="t1-i3-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
    </div><!-- Espumantes -->
    <div id="sec-2" class="section-block scroll-mt-16 mb-2"><img data-template-id="img-cat-2" class="canva-image w-full h-40 object-cover rounded-lg mb-3" loading="lazy">
     <div class="mb-3">
      <span class="cat-plate"><span data-template-id="cat-2" class="canva-text text-white uppercase text-sm tracking-wide" style="font-family:'Permanent Marker',cursive"></span></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t2-i0-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t2-i0-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t2-i1-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t2-i1-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
    </div><!-- Destilados -->
    <div id="sec-3" class="section-block scroll-mt-16 mb-2">
     <div class="mb-3">
      <span class="cat-plate"><span data-template-id="cat-3" class="canva-text text-white uppercase text-sm tracking-wide" style="font-family:'Permanent Marker',cursive"></span></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t3-i0-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t3-i0-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t3-i1-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t3-i1-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t3-i2-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t3-i2-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t3-i3-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t3-i3-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t3-i4-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t3-i4-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t3-i5-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t3-i5-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t3-i6-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t3-i6-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t3-i7-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t3-i7-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t3-i8-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t3-i8-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t3-i9-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t3-i9-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t3-i10-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t3-i10-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t3-i11-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t3-i11-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t3-i12-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t3-i12-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
    </div><!-- Bebidas Sin Alcohol -->
    <div id="sec-4" class="section-block scroll-mt-16 mb-2">
     <div class="mb-3">
      <span class="cat-plate"><span data-template-id="cat-4" class="canva-text text-white uppercase text-sm tracking-wide" style="font-family:'Permanent Marker',cursive"></span></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t4-i0-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t4-i0-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t4-i1-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t4-i1-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t4-i2-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t4-i2-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t4-i3-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t4-i3-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t4-i4-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t4-i4-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t4-i5-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t4-i5-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t4-i6-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t4-i6-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t4-i7-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t4-i7-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
    </div><!-- Entradas -->
    <div id="sec-5" class="section-block scroll-mt-16 mb-2"><img data-template-id="img-cat-5" class="canva-image w-full h-40 object-cover rounded-lg mb-3" loading="lazy">
     <div class="mb-3">
      <span class="cat-plate"><span data-template-id="cat-5" class="canva-text text-white uppercase text-sm tracking-wide" style="font-family:'Permanent Marker',cursive"></span></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t5-i0-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t5-i0-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t5-i1-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t5-i1-d" class="canva-text block text-gray-400 text-xs"></span>
      </div><span data-template-id="t5-i1-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t5-i2-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t5-i2-d" class="canva-text block text-gray-400 text-xs"></span>
      </div><span data-template-id="t5-i2-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t5-i3-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t5-i3-d" class="canva-text block text-gray-400 text-xs"></span>
      </div>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t5-i4-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t5-i4-d" class="canva-text block text-gray-400 text-xs"></span>
      </div>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t5-i5-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t5-i5-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
    </div><!-- Burgers -->
    <div id="sec-6" class="section-block scroll-mt-16 mb-2"><img data-template-id="img-cat-6" class="canva-image w-full h-40 object-cover rounded-lg mb-3" loading="lazy">
     <div class="mb-3">
      <span class="cat-plate"><span data-template-id="cat-6" class="canva-text text-white uppercase text-sm tracking-wide" style="font-family:'Permanent Marker',cursive"></span></span>
     </div>
     <p data-template-id="t6-col" class="canva-text text-gray-400 text-xs mt-1 mb-2"></p>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t6-i0-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t6-i0-d" class="canva-text block text-gray-400 text-xs"></span>
      </div>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t6-i1-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t6-i1-d" class="canva-text block text-gray-400 text-xs"></span>
      </div>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t6-i2-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t6-i2-d" class="canva-text block text-gray-400 text-xs"></span>
      </div>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t6-i3-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t6-i3-d" class="canva-text block text-gray-400 text-xs"></span>
      </div>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t6-i4-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t6-i4-d" class="canva-text block text-gray-400 text-xs"></span>
      </div>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t6-i5-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t6-i5-d" class="canva-text block text-gray-400 text-xs"></span>
      </div>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t6-i6-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t6-i6-d" class="canva-text block text-gray-400 text-xs"></span>
      </div>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t6-i7-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t6-i7-d" class="canva-text block text-gray-400 text-xs"></span>
      </div>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t6-i8-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t6-i8-d" class="canva-text block text-gray-400 text-xs"></span>
      </div>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t6-i9-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t6-i9-d" class="canva-text block text-gray-400 text-xs"></span>
      </div>
     </div>
    </div><!-- Extras -->
    <div id="sec-7" class="section-block scroll-mt-16 mb-2"><img data-template-id="img-cat-7" class="canva-image w-full h-40 object-cover rounded-lg mb-3" loading="lazy">
     <div class="mb-3">
      <span class="cat-plate"><span data-template-id="cat-7" class="canva-text text-white uppercase text-sm tracking-wide" style="font-family:'Permanent Marker',cursive"></span></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t7-i0-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t7-i0-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t7-i1-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t7-i1-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t7-i2-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t7-i2-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t7-i3-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t7-i3-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t7-i4-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t7-i4-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
    </div><!-- Pizzas -->
    <div id="sec-8" class="section-block scroll-mt-16 mb-2"><img data-template-id="img-cat-8" class="canva-image w-full h-40 object-cover rounded-lg mb-3" loading="lazy">
     <div class="mb-3">
      <span class="cat-plate"><span data-template-id="cat-8" class="canva-text text-white uppercase text-sm tracking-wide" style="font-family:'Permanent Marker',cursive"></span></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t8-i0-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t8-i0-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t8-i1-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t8-i1-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t8-i2-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t8-i2-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t8-i3-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t8-i3-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t8-i4-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t8-i4-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t8-i5-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t8-i5-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t8-i6-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t8-i6-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t8-i7-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t8-i7-d" class="canva-text block text-gray-400 text-xs"></span>
      </div><span data-template-id="t8-i7-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t8-i8-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t8-i8-d" class="canva-text block text-gray-400 text-xs"></span>
      </div>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t8-i9-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t8-i9-d" class="canva-text block text-gray-400 text-xs"></span>
      </div><span data-template-id="t8-i9-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
    </div><!-- Ensaladas -->
    <div id="sec-9" class="section-block scroll-mt-16 mb-2"><img data-template-id="img-cat-9" class="canva-image w-full h-40 object-cover rounded-lg mb-3" loading="lazy">
     <div class="mb-3">
      <span class="cat-plate"><span data-template-id="cat-9" class="canva-text text-white uppercase text-sm tracking-wide" style="font-family:'Permanent Marker',cursive"></span></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t9-i0-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t9-i0-d" class="canva-text block text-gray-400 text-xs"></span>
      </div><span data-template-id="t9-i0-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t9-i1-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t9-i1-d" class="canva-text block text-gray-400 text-xs"></span>
      </div><span data-template-id="t9-i1-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t9-i2-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div><span data-template-id="t9-i2-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
    </div><!-- Milanesas -->
    <div id="sec-10" class="section-block scroll-mt-16 mb-2">
     <div class="mb-3">
      <span class="cat-plate"><span data-template-id="cat-10" class="canva-text text-white uppercase text-sm tracking-wide" style="font-family:'Permanent Marker',cursive"></span></span>
     </div>
     <p data-template-id="t10-sub" class="canva-text text-gray-400 text-xs mb-2"></p>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t10-i0-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t10-i0-d" class="canva-text block text-gray-400 text-xs"></span>
      </div>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t10-i1-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t10-i1-d" class="canva-text block text-gray-400 text-xs"></span>
      </div>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t10-i2-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t10-i2-d" class="canva-text block text-gray-400 text-xs"></span>
      </div>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t10-i3-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t10-i3-d" class="canva-text block text-gray-400 text-xs"></span>
      </div>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t10-i4-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t10-i4-d" class="canva-text block text-gray-400 text-xs"></span>
      </div>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t10-i5-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t10-i5-d" class="canva-text block text-gray-400 text-xs"></span>
      </div>
     </div>
    </div><!-- Tacos -->
    <div id="sec-11" class="section-block scroll-mt-16 mb-2"><img data-template-id="img-cat-11" class="canva-image w-full h-40 object-cover rounded-lg mb-3" loading="lazy">
     <div class="mb-3">
      <span class="cat-plate"><span data-template-id="cat-11" class="canva-text text-white uppercase text-sm tracking-wide" style="font-family:'Permanent Marker',cursive"></span></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t11-i0-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t11-i0-d" class="canva-text block text-gray-400 text-xs"></span>
      </div><span data-template-id="t11-i0-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t11-i1-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t11-i1-d" class="canva-text block text-gray-400 text-xs"></span>
      </div>
     </div>
    </div><!-- Sándwiches -->
    <div id="sec-12" class="section-block scroll-mt-16 mb-2">
     <div class="mb-3">
      <span class="cat-plate"><span data-template-id="cat-12" class="canva-text text-white uppercase text-sm tracking-wide" style="font-family:'Permanent Marker',cursive"></span></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t12-i0-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t12-i0-d" class="canva-text block text-gray-400 text-xs"></span>
      </div><span data-template-id="t12-i0-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t12-i1-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span><span data-template-id="t12-i1-d" class="canva-text block text-gray-400 text-xs"></span>
      </div><span data-template-id="t12-i1-p" class="canva-text text-cyan-300 text-sm font-medium whitespace-nowrap"></span>
     </div>
    </div><!-- Postres -->
    <div id="sec-13" class="section-block scroll-mt-16 mb-2">
     <div class="dessert-carousel mb-1" aria-label="Fotos de postres; desliza para ver más"><img data-template-id="img-cat-13" class="canva-image w-full h-40 object-cover rounded-lg" loading="lazy"> <img data-template-id="img-dessert-1" class="canva-image w-full h-40 object-cover rounded-lg" loading="lazy"> <img data-template-id="img-dessert-2" class="canva-image w-full h-40 object-cover rounded-lg" loading="lazy"> <img data-template-id="img-dessert-3" class="canva-image w-full h-40 object-cover rounded-lg" loading="lazy"> <img data-template-id="img-dessert-4" class="canva-image w-full h-40 object-cover rounded-lg" loading="lazy"> <img data-template-id="img-dessert-5" class="canva-image w-full h-40 object-cover rounded-lg" loading="lazy">
     </div>
     <div class="carousel-hint" aria-hidden="true">
      <i data-lucide="move-horizontal"></i><span data-template-id="dessert-carousel-hint" class="canva-text">Deslizá para ver más</span>
     </div>
     <div class="mb-3">
      <span class="cat-plate"><span data-template-id="cat-13" class="canva-text text-white uppercase text-sm tracking-wide" style="font-family:'Permanent Marker',cursive"></span></span>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t13-i0-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t13-i1-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t13-i2-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div>
     </div>
     <div class="menu-item flex justify-between items-baseline py-1.5 gap-3">
      <div class="min-w-0">
       <span data-template-id="t13-i3-n" class="canva-text text-gray-200 text-sm uppercase font-medium"></span>
      </div>
     </div>
    </div>
   </div>
  </main>
  <footer class="text-center py-6 px-4 border-t border-cyan-900/30 relative z-10">
   <p data-template-id="footer-address" class="canva-text text-sm"></p>
   <p data-template-id="footer-phone" class="canva-text text-sm mt-1"></p>
  </footer>
  <script src="/_sdk/f344579cd2b2cf70.editing_sdk.js" integrity="sha512-bzdgmfJ/pl/acJqgk+LGvYwJbF03Y2d6f4oZHD96WjqTnvQUZBGVAQkTDRz+fyIMjVc+AXkpwFXqDYLeHDMLSw=="></script>
  <script>
    const sections = document.querySelectorAll('.section-block:not(#sec-9)');
    const buttons = document.querySelectorAll('#cat-nav .category-btn');
    const obs = new IntersectionObserver(entries => {
      entries.forEach(e => {
        if (e.isIntersecting) {
          const idx = [...sections].indexOf(e.target);
          buttons.forEach((b, i) => b.classList.toggle('active', i === idx));
          buttons[idx]?.scrollIntoView({behavior:'smooth',block:'nearest',inline:'center'});
        }
      });
    }, {threshold: 0.2, rootMargin: '-60px 0px -50% 0px'});
    sections.forEach(s => obs.observe(s));
    lucide.createIcons();
  </script>
 </body>
</html>
