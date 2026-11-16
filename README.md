# Escola de Atenas em 3D

Percurso interativo pela *Escola de Atenas*, afresco de Rafael Sanzio (1509 a 1511, Palácio Apostólico, Vaticano). A câmera entra na pintura e para diante dos personagens.

A página tem três roteiros:

- **Slides:** a apresentação completa (22 slides, iguais ao PowerPoint). Nos slides dos atos (9 a 12 e 14), o slide aparece inteiro, encolhe para o lado e a câmera entra na pintura no ato correspondente (Pitágoras, Sócrates, Euclides com Ptolomeu e Zoroastro, Hipátia, Platão e Aristóteles). O slide 13 (Hipátia de Alexandria) fica inteiro na tela, sem o 3D. Do slide 15 em diante, segue só com os slides. Endereço: `olimarborges.github.io/escola-de-atenas/#slides`, ou o botão "Slides" na barra. Teclas: setas, espaço ou passador para avançar e voltar, `S` para alternar entre o slide inteiro e o 3D, `F` para tela cheia e `B` para tela preta.
- **Apresentação (padrão):** abertura e cinco atos. Uma escola que nunca existiu; Ato I, Pitágoras; Ato II, Sócrates; Ato III, Euclides; Ato IV, Hipátia de Alexandria; Ato V, Platão e Aristóteles. Endereço: `olimarborges.github.io/escola-de-atenas/`
- **Percurso completo:** dez paradas, com Heráclito, Protágoras e os sofistas, Diógenes, Ptolomeu e o fim com as linhas de perspectiva. Endereço: `olimarborges.github.io/escola-de-atenas/#completo`, ou o botão "Percurso completo" na barra (no percurso completo, o botão "Apresentação" volta ao roteiro).

Feito para a sala de matemática e geometria da semana da ciência e da filosofia da Acrópole.

## Como usar

- **Avançar e voltar:** setas, espaço ou passador de slides. No celular, deslize para o lado.
- **Roteiro do apresentador:** tecla `N`.
- **Tela cheia:** tecla `F`.
- **Modo automático (para TV):** tecla `A` ou botão "Automático". Avança sozinho, em loop, com uma barra mostrando o tempo de cada parada. Qualquer navegação manual desliga. Para abrir já no automático, use `#auto` (apresentação) ou `#completo-auto` (percurso completo).
- **Ir direto a uma parada:** teclas `1` a `9` e `0`, ou um link como `#parada-3` (apresentação) ou `#completo-parada-7` (percurso completo).

## Textos

As explicações seguem a apostila *A Escola de Atenas: Arte, Filosofia e as Tradições do Conhecimento* (Cristiano Born). Hipóteses do curso aparecem marcadas como hipóteses.

## Como foi feito

- A imagem da obra vem da foto de 2024 publicada no Wikimedia Commons (20.111 × 13.936 px, domínio público, Public Domain Mark), reduzida para 7.000 px e alinhada à cena.
- A profundidade de cada ponto da pintura foi estimada com Depth Anything e calibrada pela arquitetura pintada, para que as figuras tenham relevo.
- O fundo por trás das figuras foi reconstruído para que a câmera possa se mover sem deixar buracos.
- A cena é renderizada com three.js. Tudo fica num único `index.html`, com as imagens embutidas.

Rafael não deixou legendas: várias identificações de personagens são discutidas.

## Requisitos

Navegador com WebGL e conexão com a internet (o three.js e as fontes vêm de CDN). Para projetar, prefira um computador com placa de vídeo razoável.
