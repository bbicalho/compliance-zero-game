# Compliance Zero Game

Jogo de plataforma pixel art satirizando o escândalo do Banco Master.
Todo o jogo está em um único arquivo: `index.html`.

## Stack
- HTML5 Canvas puro, sem dependências
- JavaScript vanilla, tudo num único <script>
- Publicado via GitHub Pages em https://bbicalho.github.io/compliance-zero-game

## Como publicar
git add index.html
git commit -m "descrição da mudança"
git push
# Site atualiza em ~30 segundos

## Estrutura do código (index.html)
- `initGame / loadLevel` — estado do jogo
- `drawBg` — backgrounds por tema (bank/airport/stf)
- `drawPlatform / drawPlayer / drawEnemy / drawCDB / drawGoal` — sprites
- `updatePlayer / updateEnemies / updateParticles` — física e lógica
- `LEVELS[]` — definição das 3 fases (plataformas, inimigos, colecionáveis)
- `loop()` — game loop principal (requestAnimationFrame)

## Personagens
- Jogador: correntista com camisa azul
- Lobista: terno risca-de-giz + maleta dourada
- Fantasma CDB: certificado flutuante "140% CDI"
- Toga: ministro STF com peruca branca + martelo

## Features pendentes (próximas)
- Tutorial visual na fase 1
- Tela de pausa (tecla P)
- Contador CDBs coletados/total
- Splash screen inicial
- Boss Vorcaro na fase 3
- Power-ups (Relatório da PF, Tornozeleira)
- Dificuldade progressiva entre fases
