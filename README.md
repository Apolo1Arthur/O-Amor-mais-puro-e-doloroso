echo "# O-Amor-mais-puro-e-doloroso" >> README.md 
git init 
git add README.md 
git commit -m "primeiro commit" 
git branch -M main 
git remote add origin https://github.com/Apolo1Arthur/O-Amor-mais-puro-e-doloroso.git
 git push -u origin main

 <!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mensagem para Kamille</title>
  <style>
    body {
      background: url('fundo.jpg') no-repeat center center fixed;
      background-size: cover;
      color: #f5f5f5;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 20px;
      line-height: 1.8;
    }

    .container {
      max-width: 800px;
      margin: 50px auto;
      background-color: rgba(0, 0, 0, 0.7);
      border-radius: 10px;
      padding: 30px;
      box-shadow: 0 0 15px rgba(0,0,0,0.6);
    }

    h1 {
      text-align: center;
      margin-bottom: 30px;
      font-size: 28px;
      color: #ffffff;
    }

    p {
      margin-bottom: 20px;
    }

    audio {
      display: none;
    }

    .audio-controls {
      text-align: center;
      margin-top: 20px;
    }

    .audio-controls button {
      background-color: #4CAF50;
      color: white;
      padding: 10px 20px;
      font-size: 16px;
      border: none;
      cursor: pointer;
      border-radius: 5px;
      margin: 0 10px;
    }

    .audio-controls button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Mensagem para Kamille</h1>

    <p>Kamille...</p>
    <p>Faz uma semana que eu tô com uma mensagem sua guardada aqui na cabeça. Toda vez que eu tento responder, parece que o mundo me trava...</p>
    <p>Não foi porque eu esqueci de você. Nunca foi.</p>
    <p>É que eu tô de castigo. Longe do celular, longe de tudo... menos de você.</p>
    <p>Eu pensei em sair com meu uniforme da escola, pegar o violão, me sentar na beira de uma estrada deserta, e mandar essa mensagem como se fosse um grito sussurrado pra você.</p>
    <p>Porque, mesmo sem conseguir falar, eu carrego você comigo todos os dias.</p>
    <p>Eu não sou bom com palavras... mas eu tô tentando.</p>
    <p>Tentando ser alguém que te mereça, mesmo que a distância me faça parecer ausente.</p>
    <p>A verdade é que você mora em mim.</p>
    <p>E mesmo sem poder te responder todo dia, eu não passo um segundo sem sentir você aqui dentro.</p>
    <p>Eu te amo.</p>
    <p>E só queria que você soubesse... que até em silêncio, eu tô com você.</p>

    <p>E teve um dia em que eu procurei por todo o universo... só pra entender esse vazio que eu sentia. Mas bastou olhar nos seus olhos, e lá estava eu. Me encontrei ali.</p>
    <p>Você é aquele tipo de amor que chega calado, mas quando entra, ocupa tudo. Aquilo que a gente sente e não explica. Aquilo que até a música tenta, mas nunca alcança.</p>
    <p>Quando o mundo parecia ruir, você foi minha única certeza.</p>
    <p>É estranho... como uma música pode falar tanto da gente. E essa, Kamille... essa parece ter sido feita com a minha alma, só pra tocar a sua.</p>
    <p>Eu fecho os olhos, ouço essa canção, e de repente é como se eu estivesse te abraçando.</p>
    <p>Então, se um dia você ouvir ela por aí, e sentir um aperto no peito... saiba que sou eu. Sentindo você daqui.</p>

    <p>Com todo o meu amor,</p>
    <p>Apolo Arthur</p>

    <!-- Título da música -->
    <h2 style="text-align: center; color: #ffffff;">"This I Love" - Guns N' Roses</h2>

    <!-- Controles do áudio -->
    <div class="audio-controls">
      <button id="play-btn">Play</button>
      <button id="pause-btn" style="display: none;">Pause</button>
    </div>

    <!-- Áudio -->
    <audio id="audio" loop>
      <source src="audio12.mp3" type="audio/mpeg">
      Seu navegador não suporta áudio.
    </audio>
  </div>

  <script>
    // Obter os elementos do áudio e dos botões
    const audio = document.getElementById('audio');
    const playButton = document.getElementById('play-btn');
    const pauseButton = document.getElementById('pause-btn');

    // Função para reproduzir o áudio
    playButton.addEventListener('click', function() {
      audio.play();
      playButton.style.display = 'none';
      pauseButton.style.display = 'inline-block';
    });

    // Função para pausar o áudio
    pauseButton.addEventListener('click', function() {
      audio.pause();
      playButton.style.display = 'inline-block';
      pauseButton.style.display = 'none';
    });
  </script>
</body>
</html>
