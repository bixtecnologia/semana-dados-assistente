# Semana de Dados - Assistente


Código apresentando durante o tutorial Como treinar o ChatGPT com seus dados na Semana de Dados 2023


### Objetivo

Aproveitar do conteúdo já disponível no site da empresa para criar um assistente que possa responder questionamentos dos usuários e clientes.

### Como

Extração de dados textuais de um site através de web scrapping.

Utilizando os texto do site vamos utilizar de embeddings para extrair o significado das palavras em um texto através da similaridade semântica.

O embedding será utilizado como contexto para criar um Conhecimento Customizado ou Custom Knowledge ao "ChatGPT". Assim, o assistente irá responder perguntas com base no conhecimento específico que foi disponibilizado ao assistente.

Disponibilizar uma interface onde o usuário pode fazer os questionamentos de forma simples


### Primeiros passos

Criar uma conta em:

https://platform.openai.com/

Criar uma nova API key em :

https://platform.openai.com/account/api-keys

Anotar essa chave gerada em algum lugar, ao fechar a janelas você não irá ter mais acesso, a menos que crie uma chave nova

### Referência

https://github.com/openai/openai-cookbook/blob/main/apps/web-crawl-q-and-a/web-qa.py
