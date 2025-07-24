<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rafaela Fialho</title>
  <style>
    /* Estilos gerais */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      color: #333;
    }

    /* Container principal */
    .container {
      text-align: center;
      background-color: #ffffff;
      border: 2px solid #00274d; /* Azul escuro */
      border-radius: 12px;
      padding: 25px;
      box-shadow: 0 6px 10px rgba(0, 0, 0, 0.1);
      max-width: 400px;
      width: 90%;
    }

    /* Nome no topo */
    .name {
      font-size: 28px;
      font-weight: bold;
      color: #000000; /* Preto */
      margin-bottom: 15px;
      border-bottom: 2px solid #d32f2f; /* Linha vermelha abaixo do nome */
      display: inline-block;
      padding-bottom: 5px;
    }

    /* Informações de contato */
    .contact-info {
      font-size: 18px;
      line-height: 1.8;
      margin-top: 20px;
    }

    .contact-info p {
      margin: 10px 0;
    }

    .contact-info a {
      color: #000000; /* Preto */
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s ease;
    }

    .contact-info a:hover {
      color: #d32f2f; /* Vermelho ao passar o mouse */
    }

    /* Botão de ação */
    .action-button {
      margin-top: 20px;
      display: inline-block;
      background-color: #00274d; /* Azul escuro */
      color: #ffffff;
      text-decoration: none;
      font-size: 16px;
      font-weight: bold;
      padding: 10px 20px;
      border-radius: 8px;
      transition: background-color 0.3s ease;
    }

    .action-button:hover {
      background-color: #d32f2f; /* Vermelho ao passar o mouse */
    }

    /* Rodapé */
    footer {
      margin-top: 20px;
      font-size: 12px;
      color: #777;
    }

    /* Estilos para dispositivos móveis */
    @media (max-width: 480px) {
      .container {
        padding: 20px;
      }

      .name {
        font-size: 24px;
      }

      .contact-info {
        font-size: 16px;
      }

      .action-button {
        font-size: 14px;
        padding: 8px 16px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Nome -->
    <div class="name">Rafaela Fialho</div>

    <!-- Informações de contato -->
    <div class="contact-info">
      <p>Email: <a href="mailto:rafaela.fialho@primemro.com.br">rafaela.fialho@primemro.com.br</a></p>
      <p>Celular: <a href="tel:+5521999646531">21 99964-6531</a></p>
    </div>

    <!-- Botão de ação -->
    <a href="mailto:rafaela.fialho@primemro.com.br" class="action-button">Entrar em Contato</a>

    <!-- Rodapé -->
    <footer>
      <p>QR Code Website - Minimalista</p>
    </footer>
  </div>
</body>
</html>
