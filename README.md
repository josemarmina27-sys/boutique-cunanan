# boutique-cunanan
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Boutique Cunanan | Moda Feminina</title>
  <style>
    body {
      margin: 0;
      font-family: 'Helvetica Neue', Arial, sans-serif;
      background: #fffaf7;
      color: #333;
    }
    header {
      background: linear-gradient(135deg, #f2a1b3, #e88fa4);
      color: #fff;
      padding: 60px 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.8rem;
      letter-spacing: 3px;
    }
    header p {
      margin-top: 12px;
      font-size: 1.2rem;
      opacity: 0.95;
    }
    nav {
      margin-top: 25px;
    }
    nav a {
      color: #fff;
      margin: 0 12px;
      text-decoration: none;
      font-weight: 500;
    }
    section {
      padding: 70px 20px;
      max-width: 1200px;
      margin: auto;
    }
    .about {
      text-align: center;
    }
    .about h2 {
      font-size: 2.2rem;
      margin-bottom: 20px;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 25px;
    }
    .card {
      background: #fff;
      border-radius: 16px;
      box-shadow: 0 15px 30px rgba(0,0,0,0.1);
      padding: 20px;
      text-align: center;
      transition: transform 0.3s ease;
    }
    .card:hover {
      transform: translateY(-6px);
    }
    .card img {
      width: 100%;
      border-radius: 14px;
    }
    .card h3 {
      margin: 15px 0 8px;
    }
    .card p {
      font-size: 0.95rem;
    }
    .card span {
      display: block;
      margin-top: 10px;
      font-weight: bold;
    }
    .card a {
      display: inline-block;
      margin-top: 12px;
      padding: 10px 22px;
      background: #e88fa4;
      color: #fff;
      text-decoration: none;
      border-radius: 25px;
      font-size: 0.9rem;
    }
    .cta {
      text-align: center;
      background: #fde4ea;
      border-radius: 20px;
    }
    .cta a {
      display: inline-block;
      margin: 15px;
      padding: 15px 32px;
      background: #e88fa4;
      color: #fff;
      text-decoration: none;
      border-radius: 30px;
      font-weight: bold;
    }
    .whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25d366;
      color: #fff;
      padding: 15px 20px;
      border-radius: 50px;
      text-decoration: none;
      font-weight: bold;
      box-shadow: 0 10px 25px rgba(0,0,0,0.25);
    }
    footer {
      background: #f2a1b3;
      color: #fff;
      text-align: center;
      padding: 25px;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

<header>
  <div style="width:160px;height:80px;margin:0 auto 20px;border-radius:12px;background:rgba(255,255,255,0.25);display:flex;align-items:center;justify-content:center;font-weight:bold;letter-spacing:1px;">LOGO</div>
  <p>Moda feminina que valoriza sua beleza, autoestima e estilo</p>
  <nav>
    <a href="https://www.instagram.com/boutique_cunanan/" target="_blank" title="Instagram">📸</a>
    <a href="https://www.facebook.com/boutiquecunanan.cunanan" target="_blank" title="Facebook">📘</a>
    <a href="#sobre">Sobre</a>
    <a href="#colecao">Coleção</a>
    <a href="#contato">Contato</a>
  </nav>
</header>

<section id="sobre" class="about">
  <h2>Sobre a Boutique</h2>
  <p>
    A Boutique Cunanan foi criada para mulheres que amam se sentir confiantes, elegantes e únicas.
    Trabalhamos com <strong>pronta entrega</strong>, para você comprar hoje e receber rápido, sem espera e sem complicação.
  </p>
</section>

<section id="colecao">
  <h2 style="text-align:center; margin-bottom:20px;">Nossa Coleção</h2>
  <p style="text-align:center; margin-bottom:40px; font-weight:500;">📦 Pronta entrega • Envio rápido para você arrasar sem esperar</p>
  <div class="products">
    <div class="card">
      <div style="width:100%;height:420px;border-radius:14px;background:linear-gradient(135deg,#f6c1cf,#fce4ea);display:flex;align-items:center;justify-content:center;font-weight:bold;color:#b65c75;">LOOK 1</div>
      <h3>Vestido Elegance</h3>
      <p>Elegância que valoriza seu corpo e te destaca em qualquer ocasião</p>
      
      <a href="https://wa.me/55922835858" target="_blank">Comprar</a>
    </div>
    <div class="card">
      <div style="width:100%;height:420px;border-radius:14px;background:linear-gradient(135deg,#f2a1b3,#fde4ea);display:flex;align-items:center;justify-content:center;font-weight:bold;color:#b65c75;">LOOK 2</div>
      <h3>Conjunto Modern</h3>
      <p>Conforto, estilo e versatilidade para elevar seu look diário</p>
      
      <a href="https://wa.me/55922835858" target="_blank">Comprar</a>
    </div>
    <div class="card">
      <div style="width:100%;height:420px;border-radius:14px;background:linear-gradient(135deg,#e88fa4,#fde4ea);display:flex;align-items:center;justify-content:center;font-weight:bold;color:#b65c75;">LOOK 3</div>
      <h3>Acessórios Premium</h3>
      <p>O toque final que transforma qualquer produção</p>
      
      <a href="https://wa.me/55922835858" target="_blank">Comprar</a>
    </div>
  </div>
</section>

<section id="contato" class="cta">
  <h2>📍 Atendimento Presencial</h2>
  <p style="font-weight:500;">Atendemos presencialmente em Morro Bento</p>
  <p><strong>Loja de vestuário para mulher</strong></p>
  <p>❌ Não aceitamos devolução</p>

  <p style="margin-top:15px;">
    <strong>Endereço:</strong><br>
    Avenida 21 de Janeiro, Morro Bento<br>
    Na rotunda do KFC, para quem vem da UGP em direção à Multi_Peril
  </p>

  <p style="margin-top:10px;">ℹ️ <strong>Contato:</strong> 922 835 858</p>

  <div style="margin:25px 0; border-radius:16px; overflow:hidden; box-shadow:0 10px 25px rgba(0,0,0,0.15);">
    <iframe src="https://www.google.com/maps?q=Avenida+21+de+Janeiro+Morro+Bento&output=embed" width="100%" height="300" style="border:0;" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
  </div>

  <a href="https://waze.com/ul/hkq3m7uwxy" target="_blank">🧭 Como chegar (Waze)</a>
  <a href="https://www.instagram.com/boutique_cunanan/" target="_blank">Visitar Instagram</a>
  <a href="https://www.facebook.com/boutiquecunanan.cunanan" target="_blank">Visitar Facebook</a>
  <div style="margin-top:40px;">
    <h3 style="margin-bottom:15px;">Acompanhe no Instagram</h3>
    <iframe src="https://www.instagram.com/boutique_cunanan/embed" width="100%" height="480" frameborder="0" scrolling="no" allowtransparency="true"></iframe>
  </div>

  <div style="margin-top:40px;">
    <h3 style="margin-bottom:15px;">Siga no Facebook</h3>
    <iframe src="https://www.facebook.com/plugins/page.php?href=https://www.facebook.com/boutiquecunanan.cunanan&tabs=timeline&width=340&height=500" width="100%" height="500" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowfullscreen="true"></iframe>
    <br><br>
    <a href="https://www.facebook.com/boutiquecunanan.cunanan" target="_blank" style="display:inline-block;padding:12px 28px;background:#1877f2;color:#fff;border-radius:30px;text-decoration:none;font-weight:bold;">👍 Seguir no Facebook</a>
  </div>
</section>

<footer>
  <p>📍 Avenida 21 de Janeiro, Morro Bento – Rotunda do KFC</p>
  <p>ℹ️ 922 835 858</p>
  <p>© 2026 Boutique Cunanan • Todos os direitos reservados</p>
</footer>

<a class="whatsapp" href="https://wa.me/55922835858" target="_blank">💬 WhatsApp</a>

</body>
</html>

