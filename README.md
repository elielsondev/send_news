### Quero criar uma automação no N8N para enviar as principais nóticias do dia para os usuários cadastrados.

#### Público ou responsável:
    Jornalismo e Edição

#### Resultado esperado:
    Envia todos os dias e-mail com as principais notícias em destaque.


#### Ferramentas envolvidas:
    Google Forms, Google Sheets e Gmail.

### Fluxo desejado:
1. Receber uma nova resposta do formulário.
2. Registrar os dados na planilha.
3. A partir das 6h o fluxo á disparado.
4. O agente AI faz uma busca as principais nóticias do dia.
5. O agente AI cria a estrutura com as notícias que seram enviadas.
6. Planilha com os e-mails cadastrados.
6. Captura nome e e-mails da planilha.
7. O loop que captura um nome e e-mail por vez.
8. Envia e-mail com as principais notícias.

### Regras importantes:
    Nome e e-mail dos usuários ao preencher formulário de cadastro de novos usuários são obrigatórios.


### Atue como um especialista em N8N.

### Crie uma automação para enviar e-mails com as principais nótícias do dia para as pessoas que se cadastrarem pelo formulário.

#### Público:
    Público Geral

#### Ferramentas envolvidas:
    Google Forms, Google Sheets e Gmail.

#### Fluxo:
    Recebe nome e e-mail enviados pelo forms do google, esses dados são salvos na planilha, toda manhã às 06h 
    serão enviados para todos os e-mails cadastrados.

#### Regras:
    O e-mail deve ser preenchido corretamente.

#### Explique quais nós do N8N devem ser utilizados e a lógica de funcionamento do workflow.
 - Schedule Trigger
 - AI Agent
 - Chat model (GEMINI) ou outro
 - Google Sheets (com a lista de cadastrados)
 - Set Fields (para pegar apenas o nome e e-mail de cada usuário)
 - Loop Over Items (para adicionar no envio apenas um e-mail por vez)
 - Gmail send a message (Envia os e-mails)
 - Wait (Aguarda 2 segundo para enviar o próximo e-mail)

<img width="1126" height="447" alt="image" src="https://github.com/user-attachments/assets/dd8d46b3-a67f-4c6e-87c9-fff90da1c03d" />

 
