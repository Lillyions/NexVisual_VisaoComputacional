<h1 align="center">Desafio 1 - Blur de Fundo</h1>

<p align="center">
  <b>Atividade pratica da trilha de Visao Computacional para aplicar deteccao facial e blur de fundo com OpenCV.</b>
</p>

## Objetivo

Implementar uma solucao simples para borrar o fundo de uma imagem, mantendo a regiao da pessoa em destaque. A proposta se aproxima do efeito usado em aplicativos de videochamada.

## Tecnica Utilizada

- Leitura e conversao de imagem com OpenCV
- Conversao para escala de cinza
- Deteccao facial com Haar Cascade
- Aplicacao de blur com `cv2.GaussianBlur`
- Recorte e substituicao da regiao preservada na imagem final

## Arquivos

- `VC_Desafio_1_Resolvido.ipynb`: notebook com a atividade resolvida
- `desafio_1.jpeg`: imagem de entrada
- `haarcascade_frontalface_default.xml`: classificador usado para deteccao facial
- `resultado_desafio_1_blur.jpeg`: imagem final gerada pela solucao

## Como Executar

Abra esta pasta no Jupyter Notebook e execute:

```bash
jupyter notebook VC_Desafio_1_Resolvido.ipynb
```

As dependencias principais sao:

```bash
pip install opencv-python matplotlib
```

## Resultado Esperado

Ao executar o notebook, a imagem original e processada para detectar a face, aplicar blur no restante da imagem e salvar o resultado em `resultado_desafio_1_blur.jpeg`.
