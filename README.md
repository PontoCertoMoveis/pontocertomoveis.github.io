<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ponto Certo Móveis</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      background-color: #fff8e1;
      color: #000;
    }

    header {
      background-color: #000;
      color: #ffcc00;
      padding: 20px;
      text-align: center;
    }

    h1 {
      margin: 0;
      font-size: 2.5em;
    }

    .content {
      padding: 30px 20px;
      text-align: center;
    }

    .content img {
      width: 90%;
      max-width: 600px;
      border-radius: 10px;
      margin: 20px 0;
    }

    .buttons {
      margin: 30px 0;
    }

    .buttons a {
      display: inline-block;
      margin: 10px;
      padding: 15px 30px;
      text-decoration: none;
      color: white;
      border-radius: 8px;
      font-weight: bold;
      transition: background 0.3s;
    }

    .whatsapp {
      background-color: #25d366;
    }

    .whatsapp:hover {
      background-color: #1ebc5d;
    }

    .instagram {
      background-color: #c2185b;
    }

    .instagram:hover {
      background-color: #a0154d;
    }

    .sobre {
      background-color: #fdd835;
      padding: 20px;
      border-radius: 10px;
      margin-top: 40px;
      color: #000;
      text-align: left;
      max-width: 800px;
      margin-left: auto;
      margin-right: auto;
    }

    footer {
      background-color: #000;
      color: #ffcc00;
      padding: 15px;
      text-align: center;
      margin-top: 40px;
      font-size: 0.9em;
    }

    @media (max-width: 600px) {
      h1 {
        font-size: 2em;
      }

      .buttons a {
        width: 80%;
        font-size: 1em;
      }

      .sobre {
        text-align: center;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Ponto Certo Móveis</h1>
    <p>Doutor Camargo - Av Andirá, Nº560</p>
  </header>

  <div class="content">
    <h2>Bem-vindo à nossa loja!</h2>
    <p>Encontre móveis usados, novos e seminovos com preços acessíveis.</p>

    <!-- Imagem representativa -->
    <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=1000&q=80" alt="Imagem de móveis">

    <div class="buttons">
      <a href="https://wa.me/5544988186966" class="whatsapp" target="_blank">
        <i class="fab fa-whatsapp"></i> Fale conosco no WhatsApp
      </a>
      <a href="https://www.instagram.com/pontocertomoveis.doutorcamargo/" class="instagram" target="_blank">
        <i class="fab fa-instagram"></i> Visite nosso Instagram
      </a>
    </div>

    <div class="sobre">
      <h3>Sobre nós</h3>
      <p>Somos a <strong>Ponto Certo Móveis</strong>, uma loja fundada em 2025 com a missão de oferecer móveis de qualidade por um preço que cabe no seu bolso. Trabalhamos com peças <strong>novas, usadas e seminovas</strong>, sempre escolhidas com cuidado para garantir conforto, estilo e economia.</p>
      <p>Seja para montar sua casa do zero ou renovar algum ambiente, aqui você encontra opções acessíveis e funcionais. Estamos em <strong>Doutor Camargo</strong>, e nosso objetivo é ajudar você a deixar seu lar ainda mais bonito e aconchegante.</p>
      <p><strong>Atendimento direto pelo WhatsApp</strong> para facilitar sua vida. Fale com a gente!</p>
      <p><strong>Proprietário:</strong> Sandro de Souza<br>
         <strong>Telefone:</strong> (44) 98818-6966</p>
    </div>
  </div>

  <footer>
    &copy; 2025 Ponto Certo Móveis - Todos os direitos reservados<br>
    Desenvolvido para Sandro de Souza
  </footer>

</body>
</html>
