# Projeto: Redução de Dimensionalidade em Imagens

Este projeto demonstra a implementação manual de algoritmos fundamentais de processamento de imagens em Python. O objetivo principal é converter uma imagem colorida para níveis de cinza e, em seguida, bazer a binarização para obter uma versão em preto e branco, evidenciando o conceito de **redução de dimensionalidade**.

---

### **Objetivo**

O projeto visa implementar do zero dois algoritmos clássicos de processamento de imagens. O foco é demonstrar, por meio da manipulação direta dos dados de pixel, como a conversão para tons de cinza e a binarização são realizadas, sem o uso de funções de alto nível de bibliotecas que automatizam estas tarefas.

---

### **Metodologia**

A implementação seguiu um processo sequencial de transformação da imagem, utilizando uma abordagem manual para os cálculos e decisões sobre os pixels.

* **Conversão para Níveis de Cinza:** Para cada pixel da imagem colorida (representado por seus valores de R, G e B), foi aplicada uma **fórmula de média ponderada** para calcular um único valor de intensidade. Este processo transformou a imagem de um espaço de cor tridimensional para um unidimensional.

* **Binarização da Imagem:** A partir da imagem em tons de cinza, um **limiar (threshold)** foi definido. Cada pixel foi comparado a este limiar, e seu valor foi substituído por `0` (preto) ou `255` (branco), resultando em uma imagem com apenas duas cores.

---

### **Tecnologias Utilizadas**

| Tecnologia | Descrição |
| :--- | :--- |
| `Python` | Linguagem de programação principal. |
| `Pillow` | Biblioteca de processamento de imagens (Utilizada para carregar e salvar arquivos de imagem). |
| `Google Colab` | Ambiente de desenvolvimento (Notebooks Jupyter) baseado em nuvem. |
