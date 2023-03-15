# Bot-telegram

#### 1. Primeiro, busque o `@BotFather` no Telegram.

#### 2. Mande uma mensagem `/newbot` e siga os passos:
  - Digite o nome do seu Chatbot
  - Digite com usuário Chatbot:
        Por exemplo: chat_bot

#### 3. Uma vez criado, o `@BotFather` vai lhe dar o `TOKEN`


### Agora utilize este repositório:

#### 1. Copie ou baixe-o
  - [Download](https://github.com/yujiwillian/WatsonAssistant_Telegram.git)
  
#### 2. Existe um arquivo chamado `.env`, adicione o `TOKEN` e as credenciais do Watson Assistant.
  - O Token é gerado pelo @BotFather no Telegram. (Verifique a sua conversa com o `@BotFather` para coletar esse Token)

#### 3. Baixe e instale o Node.js (https://nodejs.org/en/)

#### 4. Abra o terminal e execute o comando `npm install --save` e os pacotes serão instalados.
- Terá que ir até o diretório do repositório para o comando executar.
Por exemplo: cd downloads 
cd Bot_Telegram
npm install --save

#### 5. Execute o comando `node app` para iniciar o servidor!

#### 6. Teste o seu bot!
 - Abra o Telegram, cheque a conversa com o `@BotFather`, pois lá terá o usuário do seu bot)
 - Só clicar e iniciar a conversa


#### 7. Troubleshooting

- "Meu servidor deu erro" Verifique se o arquivo `.env` estão com as informações corretas, pois é ela quem realiza a conexão do assistente virtual que está no Watson Assistant.

##### Os endpoints pela localidade

- Dallas: https://api.us-south.assistant.watson.cloud.ibm.com
- Washington, DC: https://api.us-east.assistant.watson.cloud.ibm.com
- Frankfurt: https://api.eu-de.assistant.watson.cloud.ibm.com
- Sydney: https://api.au-syd.assistant.watson.cloud.ibm.com
- Tokyo: https://api.jp-tok.assistant.watson.cloud.ibm.com
- London: https://api.eu-gb.assistant.watson.cloud.ibm.com
- Seoul: https://api.kr-seo.assistant.watson.cloud.ibm.com

###### Códigos e passos baseados nos: [Renato Leal](https://gist.github.com/renatodossantosleal/a963eff0b3665326f975aabf19ab37ee) e [Sayuri Mizuguchi](https://github.com/sayurimizuguchi/conversation-telegram)
