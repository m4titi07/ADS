<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Matheus Ronaldo</title>

  <style>
    body {
      background-color: #f0f4f8;
      font-family: Arial, sans-serif;
      color: #333;
      margin: 0;
      padding: 20px;
    }

    h1 {
      text-align: center;
      color: #1e90ff;
    }

    p {
      font-size: 18px;
      text-align: justify;
      max-width: 800px;
      margin: 20px auto;
    }

    button {
      display: block;
      margin: 20px auto;
      padding: 10px 20px;
      font-size: 16px;
      background-color: #1e90ff;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
    }

    button:hover {
      background-color: #0d6efd;
    }

    #mensagem {
      text-align: center;
      font-size: 18px;
      color: #1e90ff;
      margin-top: 10px;
    }

    ul {
      line-height: 2;
      margin: 20px auto;
      max-width: 600px;
    }

    .hobbies-container {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 20px;
      margin: 30px auto;
      max-width: 1000px;
    }

    .hobby {
      width: 300px;
      border-radius: 12px;
      box-shadow: 0 0 8px rgba(0, 0, 0, 0.1);
    }

    table {
      border-collapse: collapse;
      width: 90%;
      max-width: 800px;
      margin: 30px auto;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    th, td {
      border: 1px solid #ccc;
      padding: 12px;
      text-align: center;
      vertical-align: top;
    }

    /* Padronizar imagens de países */
    .pais-img {
      width: 150px;
      border-radius: 8px;
      display: block;
      margin: 0 auto 10px auto;
    }

    figcaption {
      font-size: 14px;
      color: #555;
    }

    a {
      display: block;
      text-align: center;
      font-size: 18px;
      color: #1e90ff;
      text-decoration: none;
      margin-top: 30px;
    }

    a:hover {
      color: #0d6efd;
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <h1>Olá, me chamo Matheus Ronaldo</h1>

  <p>
    Tenho 23 anos, sou um jovem que gosta de se auto-desenvolver, então estou sempre em aprendizado.Tenho o sonho de viajar para alguns países e
    também gosto de fazer algumas coisas no meu lazer, dentre essas coisas irei citar algumas logo abaixo:
  </p>

  <button onclick="mostrarMensagem()">Clique para ver uma mensagem!</button>
  <p id="mensagem"></p>

  <ul>
    <li>Gosto de jogar jogos online.</li>
    <li>Pratico futsal.</li>
    <li>Adoro ler livros.</li>
  </ul>

  <div class="hobbies-container">
    <img class="hobby" src="https://conectaja.proteste.org.br/wp-content/uploads/2022/02/jovem-jogando-no-pc-gamer.png" alt="Jogando no computador" />
    <img class="hobby" src="https://www.infoescola.com/wp-content/uploads/2008/03/futsal_1014853171-1000x666.jpg" alt="Jogando futsal" />
    <img class="hobby" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQZ9yrfWomIkEBZFzQmD0frsIc23b1PaVAG0w&s" alt="Lendo livro" />
  </div>

  <!-- Tabela com países e descrições -->
  <table>
    <thead>
      <tr>
        <th>País</th>
        <th>Imagem e descrição</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Tailândia</td>
        <td>
          <figure>
            <img class="pais-img" src="https://liveslumberparty.com/wp-content/uploads/2019/03/red-light-district-1-1-1024x684.jpg" alt="Tailândia">
            <figcaption>Vista noturna das luzes de Bangkok, capital da Tailândia.</figcaption>
          </figure>
        </td>
      </tr>
      <tr>
        <td>Rússia</td>
        <td>
          <figure>
            <img class="pais-img" src="https://weheart.moscow/wp-content/uploads/020_0507.jpg" alt="Rússia">
            <figcaption>Catedral de São Basílio, um dos marcos mais famosos de Moscou.</figcaption>
          </figure>
        </td>
      </tr>
      <tr>
        <td>Estados Unidos</td>
        <td>
          <figure>
            <img class="pais-img" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3a/Times_Square_April_2022_by_Don_Ramey_Logan.jpg/1920px-Times_Square_April_2022_by_Don_Ramey_Logan.jpg" alt="Estados Unidos">
            <figcaption>Times Square, um dos pontos turísticos mais famosos de Nova York.</figcaption>
          </figure>
        </td>
      </tr>
    </tbody>
  </table>

  <a href="https://gameplayscassi.com.br/" target="_blank" rel="noopener noreferrer">Visite o site Gameplays Cassi</a>

  <script>
    function mostrarMensagem() {
      document.getElementById("mensagem").textContent = "Tenha um ótimo dia!";
    }
  </script>

</body>
</html>
