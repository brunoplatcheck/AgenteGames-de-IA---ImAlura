# 🕹️ AgenteGames de IA - ImAlura

Este projeto implementa um sistema de agentes inteligentes especializados em jogos digitais, utilizando a biblioteca `google-adk` e o modelo `Gemini` da Google. Ele permite buscar informações detalhadas sobre jogos, comparar títulos e oferecer recomendações personalizadas.

## 📌 Funcionalidades

- 🔍 Busca de informações sobre jogos (título, críticas, notas, tempo de campanha, etc.)
- 🎯 Recomendações personalizadas de jogos
- ⚖️ Comparação entre diferentes jogos
- 🌐 Ferramentas de scraping para Metacritic e HowLongToBeat

## 🧠 Agentes Inteligentes

O sistema é composto por três agentes principais:

1. **game_info_agent** – Especializado em recuperar informações detalhadas de jogos.
2. **recommendation_agent** – Especialista em recomendar jogos com base nos interesses do usuário.
3. **comparison_agent** – Responsável por comparar jogos com base em dados objetivos e críticas.

## 🧰 Ferramentas Utilizadas

- `google-adk`
- `google-genai`
- `bs4` (BeautifulSoup)
- `requests`
- `IPython.display`

## 🔧 Como Executar

Este projeto foi desenvolvido em um ambiente do **Google Colab**. Para executá-lo:

1. Clone este repositório ou carregue o notebook `.ipynb` no Colab.
2. Instale as dependências:
   ```python
   !pip install -q google-adk google-genai beautifulsoup4 requests
