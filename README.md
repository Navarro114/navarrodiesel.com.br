# navarrodiesel.com.br
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Navarro Distribuidora de Auto Peças</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: Arial, sans-serif; line-height: 1.6; }
    header { background: #222; color: #fff; padding: 20px 0; text-align: center; }
    nav a { color: #fff; margin: 0 15px; text-decoration: none; }
    .hero { background: url('images/banner.jpg') center/cover no-repeat; height: 300px; }
    section { padding: 40px 20px; text-align: center; }
    .produtos { display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; }
    .card { border: 1px solid #ddd; width: 220px; padding: 10px; }
    .card img { width: 100%; height: auto; display: block; }
    footer { background: #333; color: #ccc; padding: 30px 20px; }
    footer .container { display: flex; flex-wrap: wrap; justify-content: space-between; max-width: 900px; margin: auto; }
    footer .col { flex: 1 1 200px; margin: 10px; }
    footer a { color: #ccc; text-decoration: none; }
    footer a:hover { text-decoration: underline; }
    .social-icons a { margin-right: 10px; font-size: 1.2em; color: #ccc; }
    .social-icons a:hover { color: #fff; }
    @media (max-width: 600px) {
      .produtos { flex-direction: column; }
      footer .container { flex-direction: column; align-items: center; }
    }
  </style>
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body>

  <header>
    <h1>Navarro Distribuidora de Auto Peças</h1>
    <nav>
      <a href="#sobre">Sobre</a>
      <a href="#produtos">Produtos</a>
      <a href="#marcas">Marcas</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <div class="hero"></div>

  <section id="sobre">
    <h2>Quem Somos</h2>
    <p>Somos especialistas em autopeças para linha diesel em Limeira/SP — rápido atendimento, estoque especializado e marcas de confiança.</p>
  </section>

  <section id="produtos">
    <h2>Principais Produtos</h2>
    <div class="produtos">
      <div class="card">
        <img src="images/filtro_mann.jpg" alt="Filtro de Óleo – Mann HU 931/5 X">
        <h3>Filtro de Óleo – Mann</h3>
      </div>
      <div class="card">
        <img src="images/oleo_lubrax.jpg" alt="Óleo 15W‑40 – Lubrax">
        <h3>Óleo 15W‑40 – Lubrax</h3>
      </div>
      <div class="card">
        <img src="images/cilindro_freio.jpg" alt="Cilindro / Compressor de Freio">
        <h3>Cilindro / Compressor de Freio</h3>
      </div>
      <div class="card">
        <img src="images/pistao.jpg" alt="Pistão com Anéis">
        <h3>Pistão com Anéis</h3>
      </div>
    </div>
  </section>

  <section id="marcas">
    <h2>Marcas Trabalhadas</h2>
    <p>Trabalhamos com Bosch, Delphi, Mahle, ZF, Mann, Lubrax e outras — qualidade certificada para linha diesel.</p>
    <!-- Inserir logos como <img src="images/bosch.png" alt="Bosch"> -->
  </section>

  <section id="contato">
    <h2>Contato</h2>
    <p><strong>Telefone:</strong> (19) 3443‑1154</p>
    <p><strong>E‑mail:</strong> <a href="mailto:contato@navarroap.com.br">contato@navarroap.com.br</a></p>
    <p><strong>Endereço:</strong><br>Rua Luiz Tank, 114 – Vila Piza, Limeira/SP – CEP 13.486‑145</p>
    <div style="position:relative; padding-bottom:50%; height:0; overflow:hidden; margin-top:20px;">
      <iframe
        width="100%"
        height="100%"
        frameborder="0"
        style="border:0; position:absolute; top:0; left:0;"
        referrerpolicy="no-referrer-when-downgrade"
        src="https://www.google.com/maps/embed/v1/place?key=AIzaSyC-532CxRb3TgkB7dHffrjQKaqwJy6iBC8&q=Rua+Luiz+Tank,+114,+Limeira+SP"
        allowfullscreen>
      </iframe>
    </div>
  </section>

  <footer>
    <div class="container">
      <div class="col">
        <h3>Navarro Auto Peças</h3>
        <p>Autopeças linha diesel – Limeira/SP</p>
      </div>
      <div class="col">
        <h4>Contato</h4>
        <p>📞 (19) 3443‑1154</p>
        <p>✉️ <a href="mailto:contato@navarroap.com.br">contato@navarroap.com.br</a></p>
      </div>
      <div class="col">
        <h4>Siga-nos</h4>
        <div class="social-icons">
          <a href="#" title="Facebook"><i class="fab fa-facebook"></i></a>
          <a href="#" title="Instagram"><i class="fab fa-instagram"></i></a>
        </div>
      </div>
    </div>
    <p style="text-align:center; margin-top:20px; font-size:0.9em; color:#888;">
      © 2025 Navarro Distribuidora de Auto Peças. Todos os direitos reservados. |
      Desenvolvido por Navarro Auto Peças
    </p>
  </footer>

</body>
</html>
