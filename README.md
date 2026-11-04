# Escola de Atenas em 3D

Percurso interativo pela *Escola de Atenas*, afresco de Rafael Sanzio (1509 a 1511, Palácio Apostólico, Vaticano). A câmera entra na pintura e para diante de nove pontos: a obra, Heráclito, Pitágoras, Sócrates, Platão e Aristóteles, Diógenes, Zoroastro, Ptolomeu e Rafael, Euclides e, no fim, as linhas de perspectiva.

Feito para a sala de matemática e geometria da semana da ciência e da filosofia da Acrópole.

## Como usar

- **Avançar e voltar:** setas, espaço ou passador de slides. No celular, deslize para o lado.
- **Roteiro do apresentador:** tecla `N`.
- **Tela cheia:** tecla `F`.
- **Ir direto a uma parada:** teclas `1` a `9`, ou um link terminado em `#parada-5`, por exemplo.

## Como foi feito

- A linha desenhada sobre a foto foi removida com reconstrução de imagem (LaMa).
- A profundidade de cada ponto da pintura foi estimada com Depth Anything e calibrada pela arquitetura pintada, para que as figuras tenham relevo.
- O fundo por trás das figuras foi reconstruído para que a câmera possa se mover sem deixar buracos.
- A cena é renderizada com three.js. Tudo fica num único `index.html`, com as imagens embutidas.

As identificações dos personagens seguem a tradição dos estudiosos. Rafael não deixou legendas, e várias delas são discutidas.

## Requisitos

Navegador com WebGL e conexão com a internet (o three.js e as fontes vêm de CDN). Para projetar, prefira um computador com placa de vídeo razoável.
