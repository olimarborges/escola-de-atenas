# Escola de Atenas em 3D

Percurso interativo pela *Escola de Atenas*, afresco de Rafael Sanzio (1509 a 1511, Palácio Apostólico, Vaticano). A câmera entra na pintura e para diante de dez pontos: a obra, Heráclito, Pitágoras, Protágoras e os sofistas, Sócrates, Platão e Aristóteles, Diógenes, Ptolomeu com o globo celeste e Rafael, Euclides e, no fim, as linhas de perspectiva.

Feito para a sala de matemática e geometria da semana da ciência e da filosofia da Acrópole.

## Como usar

- **Avançar e voltar:** setas, espaço ou passador de slides. No celular, deslize para o lado.
- **Roteiro do apresentador:** tecla `N`.
- **Tela cheia:** tecla `F`.
- **Ir direto a uma parada:** teclas `1` a `9`, ou um link terminado em `#parada-10`, por exemplo.

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
