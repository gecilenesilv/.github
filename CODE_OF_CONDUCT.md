<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GEXCERTISE | Sua Marca, Nossa Expertise</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;600;700;800&family=Playfair+Display:ital,wght@0,600;1,400&display=swap');
    body { font-family: 'Montserrat', sans-serif; }
    .font-serif-title { font-family: 'Playfair Display', serif; }
  </style>
</head>
<body class="bg-gray-50 text-slate-900">

  <!-- Faixa de Frete Grátis -->
  <div class="bg-black text-white text-xs uppercase tracking-widest py-2 px-4 text-center">
    FRETE GRÁTIS NOS PEDIDOS ACIMA DE R$ 50 - USE O CUPOM <span class="text-amber-400 font-bold">MAIS50</span>
  </div>

  <!-- Cabeçalho / Navbar -->
  <header class="bg-white border-b border-gray-200 sticky top-0 z-40">
    <div class="max-w-7xl mx-mx-auto px-4 py-4 flex items-center justify-between">
      <div class="flex items-center space-x-3">
        <div class="w-10 h-10 bg-black text-white flex items-center justify-center font-bold text-lg rounded">GEX</div>
        <div>
          <h1 class="text-xl font-extrabold tracking-wider">GEXCERTISE</h1>
          <p class="text-[10px] text-gray-500 tracking-widest uppercase">Sua marca, nossa expertise</p>
        </div>
      </div>
      <nav class="hidden md:flex space-x-6 text-sm font-semibold uppercase tracking-wider">
        <a href="#colecoes" class="hover:text-amber-600 transition">Coleção</a>
        <a href="#servicos" class="hover:text-amber-600 transition">Serviços</a>
        <a href="#videos" class="hover:text-amber-600 transition">Vídeos</a>
        <a href="#catalogo" class="hover:text-amber-600 transition">Catálogo</a>
      </nav>
      <div class="flex items-center space-x-4">
        <button onclick="toggleCart()" class="relative p-2 text-slate-800 hover:text-amber-600">
          <i class="fa-solid fa-bag-shopping text-xl"></i>
          <span id="cart-count" class="absolute -top-1 -right-1 bg-amber-500 text-black font-bold text-xs w-5 h-5 rounded-full flex items-center justify-center">0</span>
        </button>
      </div>
    </div>
  </header>

  <!-- Banner Hero Principal -->
  <section class="relative bg-slate-900 text-white py-20 px-6">
    <div class="max-w-6xl mx-auto grid md:grid-cols-2 gap-8 items-center">
      <div>
        <span class="inline-block bg-amber-500 text-black font-bold text-xs uppercase px-3 py-1 rounded mb-4">Lançamento Exclusivo</span>
        <h2 class="text-4xl md:text-5xl font-extrabold uppercase tracking-tight mb-4">IT DOESN'T GET EASIER. YOU GET BETTER.</h2>
        <p class="text-gray-300 mb-6">Conforto diário, tecido de alto desempenho e cortes autênticos para treinos e momentos do dia a dia.</p>
        <a href="#catalogo" class="inline-block bg-amber-500 text-black font-bold px-8 py-3 uppercase tracking-wider hover:bg-amber-400 transition">Confira o Catálogo</a>
      </div>
      <div class="relative bg-slate-800 p-6 rounded-lg border border-slate-700">
        <div class="text-center py-8">
          <p class="text-amber-400 font-bold text-2xl mb-2">17% OFF</p>
          <p class="text-lg uppercase tracking-wide">Na compra de 2 ou mais peças</p>
          <p class="text-sm text-gray-400 mt-2">A partir de <strong>R$ 60,00</strong></p>
        </div>
      </div>
    </div>
  </section>

  <!-- Rodapé e demais secções já presentes no canvas -->
  <footer class="bg-black text-white py-10 px-6 text-center text-sm">
    <p>© 2026 GEXCERTISE - Sua marca, nossa expertise.</p>
  </footer>

</body>
</html>
