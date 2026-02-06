# Processamento de Imagens – Operações Morfológicas

## Sobre este repositório

Este repositório é um **fork** de um projeto acadêmico de Processamento de Imagens que implementa operações morfológicas básicas sobre imagens binárias utilizando JavaScript e a API Canvas do navegador.

Estou realizando este fork para registrar oficialmente minha participação no desenvolvimento do projeto, bem como para manter uma versão sob minha responsabilidade, permitindo futuras melhorias, refatorações e evoluções individuais.

Repositório original:

https://github.com/EduardoGarzon/Morphological-Image-Processing

---

## Descrição do Projeto

O sistema permite:

* Carregar uma imagem pelo navegador
* Converter a imagem para escala de cinza
* Binarizar a imagem (preto e branco)
* Aplicar operações morfológicas:

  * Erosão
  * Dilatação
  * Abertura
  * Fechamento
* Selecionar diferentes elementos estruturantes:

  * Linha
  * Cruz
  * Quadrado

Todas as operações são executadas manualmente pixel a pixel, sem o uso de bibliotecas externas de processamento de imagem.

---

## Conceitos Aplicados

O projeto implementa conceitos fundamentais de:

* Processamento Digital de Imagens
* Transformações morfológicas
* Elementos estruturantes
* Manipulação direta de ImageData
* Manipulação de pixels via Canvas API

As operações seguem a definição clássica:

* Erosão: Remove pixels do objeto conforme o elemento estruturante.
* Dilatação: Expande pixels do objeto conforme o elemento estruturante.
* Abertura: Erosão seguida de dilatação.
* Fechamento: Dilatação seguida de erosão.

---

## Tecnologias Utilizadas

* HTML5
* CSS3
* JavaScript (Vanilla JS)
* Canvas API

Não foram utilizadas bibliotecas externas.

---

## Estrutura Geral

O fluxo principal do sistema é:

1. Upload da imagem
2. Conversão para escala de cinza
3. Binarização
4. Aplicação da operação morfológica escolhida
5. Exibição da imagem resultante

As funções principais implementadas são:

* `imgToGrayscale()`
* `imgToBinary()`
* `erodeImage()`
* `dilateImage()`
* `openImage()`
* `closeImage()`





---

## Contexto Acadêmico

- Projeto desenvolvido como atividade da disciplina de Processamento de Imagens no curso de Ciência da Computação.
