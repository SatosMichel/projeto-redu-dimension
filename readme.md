# 🖼️ Redução de Dimensionalidade em Imagens para Redes Neurais  

Este projeto foi desenvolvido como parte do **Desafio da DIO** no módulo de **Visão Computacional**.  
O objetivo é aplicar transformações em uma imagem colorida para:  

1. Converter para **escala de cinza** (0 a 255 níveis).  
2. Converter para **binarizada** (preto e branco, 0 e 255).  

---

## 🚀 Tecnologias Utilizadas
- [Python 3](https://www.python.org/)  
- [Google Colab](https://colab.research.google.com/)  
- [NumPy](https://numpy.org/) – manipulação de matrizes  
- [Matplotlib](https://matplotlib.org/) – visualização  
- [PIL (Pillow)](https://python-pillow.org/) – manipulação de imagens  

---

## 📂 Estrutura do Projeto

- `notebook.ipynb` → Notebook principal com as implementações.  
- `README.md` → Este arquivo de explicação do projeto.  

---

## 🔎 Funcionamento

### 1. Entrada (Imagem Colorida)
Imagem carregada pelo usuário.  

### 2. Conversão para Escala de Cinza
Cada pixel RGB é convertido para cinza pela fórmula:
Gray = 0.299R + 0.587G + 0.114*B


### 3. Conversão para Binarizada
A partir da **imagem colorida original**, convertemos em preto/branco usando um limiar (`threshold`, padrão = 128):  
Binary = 255 se intensidade > threshold
Binary = 0 se intensidade <= threshold

---

## ▶️ Como Executar no Google Colab

1. Abra o [Google Colab](https://colab.research.google.com/).  
2. Carregue o notebook deste repositório.  
3. Faça upload de uma imagem (`.jpg` ou `.png`).  
4. Execute todas as células → a saída mostrará as três versões:  
   - Colorida  
   - Escala de Cinza  
   - Binarizada  

---

## 📌 Observações
- O código **não usa funções prontas de conversão** de bibliotecas, apenas operações matemáticas em arrays.  
- O objetivo é **entender a redução de dimensionalidade** em imagens e sua aplicação em redes neurais.  

---

## 👨‍💻 Autor

Projeto desenvolvido por **Michel Rebouças**.

- **LinkedIn:** [Michel Santos Rebouças](https://www.linkedin.com/in/michel-santos-rebou%C3%A7as-5a81b561/)
- **Instagram:** [@satosmichel_oficial](https://www.instagram.com/satosmichel_oficial/)

---

## 🙏 Agradecimentos

Agradecimento especial à [Digital Innovation One (DIO)](https://dio.me/) pela oportunidade de aprendizado e pelo desafio proposto.
