🕹️ AgenteGames de IA - ImAlura
Este projeto implementa um sistema de agentes inteligentes especializados em jogos digitais, utilizando a biblioteca google-adk e o modelo Gemini da Google. Ele permite buscar informações detalhadas sobre jogos, comparar títulos e oferecer recomendações personalizadas.

📌 Funcionalidades
🔍 Busca de informações sobre jogos (título, críticas, notas, tempo de campanha, etc.)

🎯 Recomendações personalizadas de jogos

⚖️ Comparação entre diferentes jogos

🌐 Ferramentas de scraping para Metacritic e HowLongToBeat

🧠 Agentes Inteligentes
O sistema é composto por três agentes principais:

game_info_agent – Especializado em recuperar informações detalhadas de jogos.

recommendation_agent – Especialista em recomendar jogos com base nos interesses do usuário.

comparison_agent – Responsável por comparar jogos com base em dados objetivos e críticas.

🧰 Ferramentas Utilizadas
google-adk

google-genai

bs4 (BeautifulSoup)

requests

IPython.display

🔧 Como Executar
Este projeto foi desenvolvido em um ambiente do Google Colab. Para executá-lo:

Clone este repositório ou carregue o notebook .ipynb no Colab.

Instale as dependências:

python
Copiar
Editar
!pip install -q google-adk google-genai beautifulsoup4 requests
Configure sua chave de API:

python
Copiar
Editar
import os
from google.colab import userdata
os.environ["GOOGLE_API_KEY"] = userdata.get('GOOGLE_API_KEY')
Execute as células sequencialmente.

💡 Exemplo de Uso
python
Copiar
Editar
call_agent(game_info_agent, "Me fale sobre o jogo The Witcher 3")
call_agent(recommendation_agent, "Quero um jogo de mundo aberto com boa história")
call_agent(comparison_agent, "Compare Elden Ring com Dark Souls 3")
⚠️ Observações
A extração de dados da Metacritic e HowLongToBeat pode estar sujeita a mudanças nos sites (estrutura HTML).

A ferramenta de reviews da Steam está implementada de forma genérica e pode ser aprimorada com APIs específicas como SteamSpy.

📁 Estrutura
agentegames_de_ia_imalura.py – Versão em script Python

AgenteGames_de_IA_ImAlura.ipynb – Versão notebook do Colab

🧑‍💻 Autor
Projeto desenvolvido como parte dos estudos com IA Generativa e Agentes usando o Google ADK, inspirado em exercícios da Imersão Alura.

