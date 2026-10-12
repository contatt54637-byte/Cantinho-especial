
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Um Lugar pra Você 🌙</title>

<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  min-height: 100vh;
  font-family: Georgia, serif;
  color: #f1f3ff;
  text-align: center;
  background:
    radial-gradient(circle at 15% 20%, #526baf 1px, transparent 2px),
    radial-gradient(circle at 80% 30%, #ffffff 1px, transparent 2px),
    radial-gradient(circle at 40% 70%, #9bbaff 1px, transparent 2px),
    linear-gradient(160deg, #080e29, #172d59, #10152f);
  background-size: 90px 100px, 130px 120px, 110px 140px, cover;
}

main {
  padding: 55px 22px 40px;
  max-width: 560px;
  margin: auto;
}

.lua {
  font-size: 68px;
  margin-bottom: 12px;
  text-shadow: 0 0 30px #a9c8ff;
}

h1 {
  font-size: 35px;
  font-weight: normal;
  margin-bottom: 12px;
}

.subtitulo {
  color: #c6d5ff;
  line-height: 1.8;
  font-size: 16px;
}

button {
  display: block;
  width: 100%;
  padding: 15px 12px;
  margin: 14px 0;
  border: 1px solid #8ba9e9;
  border-radius: 14px;
  background: #ffffff12;
  color: white;
  font-size: 16px;
  font-family: Georgia, serif;
}

button:active {
  background: #7898d944;
}

#mensagem {
  display: none;
  margin-top: 25px;
  padding: 22px;
  border-radius: 18px;
  background: #ffffff12;
  border: 1px solid #9bbaff66;
  line-height: 1.9;
  white-space: pre-line;
}

footer {
  margin-top: 40px;
  color: #b5c8fa;
  font-size: 13px;
}
</style>
</head>

<body>
<main>
  <div class="lua">☾</div>

  <h1>Um Lugar pra Você</h1>

  <p class="subtitulo">
    Oi, Nana. 💙<br>
    Preparei um cantinho pra você.<br>
    Volte aqui sempre que precisar.
  </p>

  <button onclick="mostrar(0)">♡ Um abraço em palavras</button>
  <button onclick="mostrar(1)">✧ Um lembrete do seu valor</button>
  <button onclick="mostrar(2)">☁ Um motivo pra sorrir</button>
  <button onclick="mostrar(3)">💌 Uma cartinha especial</button>

  <div id="mensagem"></div>

  <footer>
    Mesmo nas noites mais escuras, as estrelas continuam lá. ✨
  </footer>
</main>

<script>
const mensagens = [
  "Se hoje estiver difícil, respire um pouquinho. Você não precisa resolver tudo de uma vez. Imagine que este cantinho é um abraço quentinho, sem cobranças e sem pressa. 💙",

  "Nana, você tem valor até nos dias em que não consegue enxergar isso. Você não precisa ser forte o tempo inteiro, agradar todo mundo ou provar que merece carinho. Você merece cuidado simplesmente por ser você. ✨",

  "Ei, sabia que o céu não deixa de ser bonito só porque algumas nuvens apareceram? ☁️ Talvez hoje não seja um dia perfeito, mas ainda podem existir pequenas coisas boas esperando por você. Não desista de percebê-las.",

  "Nana,\n\nTalvez a vida esteja diferente e talvez a gente não esteja tão perto quanto antes. Mas eu queria deixar registrado que você é uma pessoa importante para mim.\n\nFiz este pequeno lugar pensando em você, para que possa voltar quando quiser ler palavras gentis, respirar e lembrar que sua existência importa.\n\nNão precisa responder nem sentir nenhuma obrigação. Só queria que você tivesse um cantinho de carinho disponível sempre que precisasse.\n\nCuide de você, tá?\n\nCom carinho. 💙🌙"
];

function mostrar(indice) {
  const caixa = document.getElementById("mensagem");
  caixa.textContent = mensagens[indice];
  caixa.style.display = "block";
  caixa.scrollIntoView({ behavior: "smooth", block: "nearest" });
}
</script>
</body>
</html>
