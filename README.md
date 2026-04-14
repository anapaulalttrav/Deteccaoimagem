# 📸 Reconhecimento Facial de Emoções (Oficina de IA)

Este projeto foi desenvolvido durante uma oficina prática de faculdade, utilizando o ambiente *Google Colab*. O foco foi a aplicação de algoritmos de visão computacional para detectar rostos em fotografias e classificar as expressões emocionais contidas nelas.

---

## 🛠️ Tecnologias e Bibliotecas

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)

* *Python*: Linguagem utilizada para processamento dos dados.
* *Google Colab*: Plataforma em nuvem que facilitou a execução do código e o upload das imagens.
* *Haar Cascade (OpenCV)*: Algoritmo de detecção de objetos utilizado para localizar as faces nas fotos carregadas.
* *DeepFace / Keras*: Modelos utilizados para a análise e classificação da emoção detectada no recorte do rosto.

---

## 🚀 Como Funciona o Projeto

O fluxo de execução no notebook segue estes passos:

1.  *Upload da Imagem*: O script solicita que você escolha um arquivo de imagem do seu computador.
2.  *Detecção com Haar Cascade*: O código utiliza o arquivo haarcascade_frontalface_default.xml para identificar as coordenadas (x, y, largura, altura) de cada rosto na foto.
3.  *Processamento de Emoções*: Cada rosto detectado é isolado e enviado para o classificador de emoções.
4.  *Exibição Visual*: A imagem final é exibida com um quadrado ao redor do rosto e o nome da emoção (ex: "Feliz", "Neutro", "Raiva") escrito acima.

---

## 📌 Emoções que o sistema identifica:
* 😊 Felicidade
* 😢 Tristeza
* 😠 Raiva
* 😲 Surpresa
* 😐 Neutro
* 😨 Medo
* 🤢 Nojo

---

## 💻 Como Rodar no Colab

1.  Acesse o seu notebook no [Google Colab](https://colab.research.google.com/).
2.  Instale a biblioteca de suporte:
    python
    !pip install deepface
    
3.  Certifique-se de que o arquivo do *Haar Cascade* está sendo carregado corretamente pelo OpenCV.
4.  Execute a célula de upload, selecione sua foto e veja o resultado direto no console do Colab!

---
> *Aprendizado:* Durante a oficina, entendi como a detecção de objetos (Haar Cascade) funciona de forma diferente da classificação (IA de emoções), e como o Google Colab facilita o compartilhamento de projetos de Ciência de Dados.
