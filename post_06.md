# POST 06

**13/10/2026**

## O microfone visual: recuperando som a partir de vídeo

Uma aplicação diferente de computação visual é a recuperação de som a partir de imagens. Quando uma onda sonora atinge um objeto, ela faz sua superfície vibrar. Essas vibrações são tão pequenas que, na maioria das vezes, ficam abaixo do tamanho de um pixel e não podem ser percebidas a olho nu. Em 2014, pesquisadores do MIT mostraram que, filmando um objeto com uma câmera de alta velocidade e analisando esses movimentos minúsculos quadro a quadro, é possível reconstruir parcialmente o som que estava no ambiente. A técnica ficou conhecida como "microfone visual" (*visual microphone*).

Nos experimentos, objetos comuns como um saco de batatas, uma planta, uma caixa de lenços e um copo com água funcionaram como "microfones". Em um dos testes, o grupo filmou o saco de batatas enquanto uma música tocava ao lado e conseguiu recuperar o áudio apenas a partir do vídeo, sem nenhum microfone convencional. O resultado era claro o suficiente para que um aplicativo de reconhecimento musical identificasse a canção.

O funcionamento depende diretamente de conceitos de imagem digital. Cada quadro do vídeo é uma amostra da posição do objeto no tempo, então a taxa de quadros funciona como a taxa de amostragem do áudio: quanto mais quadros por segundo, mais frequências do som podem ser recuperadas. Por isso o experimento original usou câmeras de alta velocidade, com milhares de quadros por segundo. Os autores também testaram câmeras comuns, aproveitando a forma como o sensor captura a imagem linha por linha (*rolling shutter*), mas com qualidade bem inferior.

Além de áudio, a técnica também pode ser usada para analisar propriedades de materiais e estruturas a partir de como elas vibram, o que mostra que um vídeo guarda mais informação do que parece ao assistirmos a ele.

## Artigo e vídeo

- [Artigo - The Visual Microphone: Passive Recovery of Sound from Video (MIT CSAIL, SIGGRAPH 2014)](https://people.csail.mit.edu/mrub/VisualMic)
- [Vídeo - The Visual Microphone: Passive Recovery of Sound from Video](https://www.youtube.com/watch?v=FKXOucXB4a8)

---

[Voltar para a página inicial](https://github.com/PedroSZequi/CompVisual/blob/main/index.md)
