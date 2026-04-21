<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ganhe Dinheiro na Internet</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&display=swap" rel="stylesheet">
  <style>
    *{margin:0;padding:0;box-sizing:border-box}
    body{font-family:'Inter',sans-serif;background:#0b0f1a;color:#fff}
    .container{max-width:1000px;margin:auto;padding:20px}

    .hero{padding:60px 20px;text-align:center;background:radial-gradient(circle at top,#1a1f3a,#0b0f1a)}
    .hero h1{font-size:2.5rem;font-weight:800;line-height:1.2}
    .hero p{opacity:.8;margin-top:10px}

    .btn{
      display:inline-block;
      background:linear-gradient(90deg,#00ffcc,#00c2ff);
      color:#000;
      padding:15px 25px;
      font-weight:700;
      border-radius:12px;
      text-decoration:none;
      margin-top:25px;
      transition:.3s;
      box-shadow:0 10px 30px rgba(0,255,200,.2)
    }
    .btn:hover{transform:scale(1.05)}

    .section{margin-top:40px}
    .card{
      background:#12182b;
      padding:20px;
      border-radius:16px;
      margin-bottom:20px;
      box-shadow:0 10px 25px rgba(0,0,0,.3)
    }

    h2{margin-bottom:10px;font-size:1.5rem}
    p{line-height:1.6;opacity:.9}

    .grid{display:grid;gap:20px}
    @media(min-width:768px){
      .grid-2{grid-template-columns:1fr 1fr}
    }

    .highlight{color:#00ffcc;font-weight:700}

    .testimonial{font-style:italic;opacity:.9}

    .price{font-size:2rem;font-weight:800;color:#00ffcc}

    .faq-item{margin-bottom:10px}
    .faq-q{cursor:pointer;font-weight:600}
    .faq-a{display:none;opacity:.8;margin-top:5px}

    .sticky{
      position:fixed;
      bottom:15px;
      left:50%;
      transform:translateX(-50%);
      width:90%;
      max-width:400px;
      text-align:center;
      z-index:999
    }
  </style>
</head>
<body>

  <div class="hero">
    <div class="container">
      <h1>Descubra Como Ganhar Dinheiro na Internet Usando Apenas o Celular</h1>
      <p>Mesmo começando do zero e sem experiência</p>
      <a href="#" class="btn">QUERO COMEÇAR AGORA</a>
    </div>
  </div>

  <div class="container">

    <div class="section card">
      <h2>Você se identifica com isso?</h2>
      <p>- Cansado de não ter dinheiro?</p>
      <p>- Já tentou ganhar online e não conseguiu?</p>
      <p>- Quer uma renda extra sem sair de casa?</p>
    </div>

    <div class="section card">
      <h2>A Solução</h2>
      <p>Este ebook mostra um método <span class="highlight">simples e direto</span> para começar do zero e gerar renda online.</p>
    </div>

    <div class="section grid grid-2">
      <div class="card">
        <h2>O que você vai aprender</h2>
        <p>- Escolher nicho lucrativo</p>
        <p>- Vender como afiliado</p>
        <p>- Criar conteúdo que vende</p>
      </div>
      <div class="card">
        <h2>Bônus</h2>
        <p>- Ideias prontas de conteúdo</p>
        <p>- Estratégias de tráfego</p>
        <p>- Estrutura pronta de vendas</p>
      </div>
    </div>

    <div class="section card">
      <h2>Depoimentos</h2>
      <p class="testimonial">"Fiz minha primeira venda em 7 dias"</p>
      <p class="testimonial">"Hoje tenho renda online consistente"</p>
    </div>

    <div class="section card" style="text-align:center">
      <h2>Oferta Especial</h2>
      <p>De R$97 por apenas</p>
      <div class="price">R$29,90</div>
      <p>+ bônus exclusivos</p>
      <a href="#" class="btn">QUERO ACESSAR AGORA</a>
    </div>

    <div class="section card">
      <h2>Garantia</h2>
      <p>7 dias de garantia incondicional. Ou seu dinheiro de volta.</p>
    </div>

    <div class="section card">
      <h2>Perguntas Frequentes</h2>

      <div class="faq-item">
        <div class="faq-q" onclick="toggleFAQ(this)">Preciso aparecer?</div>
        <div class="faq-a">Não.</div>
      </div>

      <div class="faq-item">
        <div class="faq-q" onclick="toggleFAQ(this)">Funciona para iniciantes?</div>
        <div class="faq-a">Sim, foi feito para iniciantes.</div>
      </div>

      <div class="faq-item">
        <div class="faq-q" onclick="toggleFAQ(this)">Preciso investir?</div>
        <div class="faq-a">Pode começar sem investimento.</div>
      </div>

    </div>

  </div>

  <div class="sticky">
    <a href="#" class="btn">COMEÇAR AGORA</a>
  </div>

  <script>
    function toggleFAQ(el){
      const ans = el.nextElementSibling
      ans.style.display = ans.style.display === 'block' ? 'none' : 'block'
    }
  </script>

</body>
</html>
