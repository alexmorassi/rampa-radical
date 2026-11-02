# Rampa Radical

Jogo infantil de destruição de carros para celular: pegue velocidade, salte da rampa e destrua o carro nos obstáculos. Dois modos: **Normal** (13 fases, 7 carros, 6 rampas) e **Mega Rampa** (Planeta Terra, Buraco Negro, Vulcão, Redemoinho e Esgoto). Feito com Three.js e cannon.js.

**Jogar:** https://alexmorassi.github.io/rampa-radical/

## Mega Rampas
- **Planeta Terra**: desce do espaço até a Terra, com mega queda e estrada de ondas.
- **Buraco Negro**: o carro é sugado, gira em volta e é engolido.
- **Vulcão**: salto para dentro da cratera; a lava derrete o carro e a erupção cospe o que sobrou.
- **Redemoinho**: o redemoinho gigante no mar engole o carro e, no fundo, o megalodon e o mosassauro comem tudo.
- **Esgoto**: largada numa chaminé, cano gigante, cachoeira de esgoto e salto no piscinão de gosma; o ralo engole e o cano de saída cospe no rio.

## Muro do alvo
- O muro com o alvo no fim das pistas é feito de blocos de concreto e quebra conforme a força da batida (peso e velocidade do carro).
- Batida fraca racha os blocos; média solta um ou dois; forte abre um buraco por onde o carro passa (+1.000); muito forte faz o muro desmoronar (+2.500).

## Instalar no celular
Abra o link no navegador e use "Adicionar à Tela de Início" (iPhone: botão Compartilhar; Android: menu ⋮). O jogo abre em tela cheia com o ícone do Rampa Radical.

## Controles
- Toque no lado esquerdo/direito da tela para virar (no ar, gira o carro).
- Botão NITRO abre o foguete.
- Teclado: setas ou A/D, espaço = nitro, P = pausa, R = reinicia.

## Publicar uma versão nova
- O site é publicado a partir do ramo `gh-pages` (mantenha `main` e `gh-pages` iguais).
- O jogo confere `version.txt` ao abrir e ao voltar para o app: se o número for diferente do `APP_VER` do `index.html`, ele recarrega sozinho com a versão nova (no meio de uma corrida, espera voltar ao menu).
- A cada versão nova, aumente `APP_VER` no `index.html` e coloque o mesmo número em `version.txt`.
