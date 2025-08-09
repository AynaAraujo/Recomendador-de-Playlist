# 🎵 Recomendador de Playlists

## 📌 Descrição

Este sistema recomenda **playlists personalizadas** com base em uma música inserida pelo usuário.
A recomendação é feita por meio de **Machine Learning** e análise de similaridade, explorando dados musicais para encontrar faixas que se alinham ao perfil sonoro da música escolhida.

---

## 🚀 Tecnologias Utilizadas

* **Python** – Linguagem principal do projeto
* **Apache Spark** & **PySpark** – Processamento de grandes volumes de dados musicais
* **Spotipy** – Integração com a API do Spotify para coleta de metadados e faixas
* **NumPy** & **SciPy** – Manipulação e análise numérica
* **Scikit-image (skimage)** – Processamento e extração de características adicionais
* **Matplotlib** & **Plotly** – Visualização dos dados e insights

---

## 💡 Destaques do Projeto

* 🔍 **Recomendação inteligente** baseada em **similaridade acústica** e metadados musicais
* ⚡ Processamento otimizado com **Apache Spark**, permitindo trabalhar com grandes bases de músicas
* 📊 Visualizações interativas e exploratórias com **Plotly** e **Matplotlib**
* 🎧 Integração direta com o **Spotify** para buscar músicas e playlists


---

## ⚙️ Como Funciona

1. O usuário informa o nome de uma música ou artista.
2. O sistema coleta informações da música usando a API do Spotify.
3. Com o Spark, realiza-se a análise e busca por músicas similares no dataset.
4. O algoritmo de Machine Learning recomenda faixas e monta uma playlist personalizada.
5. Resultados são apresentados com **visualizações interativas**.

---

## 📌 Exemplo de Uso

```python
python main.py --music "Shape of You"
```

Saída esperada:

* Lista de músicas recomendadas

---
