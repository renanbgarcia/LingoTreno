# LearnQuotes

Esse � um projeto que eu fiz para come�ar a aprender Angular e typescript, al�m de fundamentos de Back-End com
Node.js e express.js, criando uma REST API que serve o back-end do aplicativo.

Rodando no Google App Engine:
https://treno-218217.appspot.com/

Eu comecei tentando fazer um web aplicativo que gera cita��es aleat�rias, agora estou tentando
expandir as funcionalidades para fazer um aplicativo de aprendizagem de idiomas usando a gera��o de
cita��e sem diversas l�nguas.

Atualmente j� foi criado:

1. Login utilizando a estrat�gia Google OAuth do Passport.js.
2. Gera��o de cita��es aleat�rias em Ingl�s e Franc�s.
3. Algumas Rotas da API.
4. Capacidade de salvar cita��es na conta do usu�rio.
5. Capacidade de salvar palavras das cita��es na conta do usu�rio, podendo adicionar significado e n�vel de conhecimento da palavra.
6. Ouvir o audio da cita��o.
7. Tradu��o da cita��o e sujest�o de tradu��o de palavras.

TODO:

1. Construir perfil do usu�rio.
2. ...
3. Adicionar m�todos de estudo/revis�o de cita��es/palavras aprendidas.
4. Consertar toda a parte de typescript :<
5. etc etc etc

Eu usei a API do MediaWiki para obter dados do WikiQuotes.
Os dados retornados da API, assim como � referenciado na documenta��o dela, n�o
s�o sem�nticos, ou seja, foi bem complicado conseguir obter os dados necess�rio corretamente
para poder chegar � uma cita��o formatada. Mas eu consegui chegar a um resultado razo�vel
com os dados vindos da API em ingl�s e franc�s. Ainda � poss�vel conseguir o mesmo com outras
l�nguas.

## Como rodar

- Baixe ou clone o reposit�rio.

- Voc� vai precisar ter o NPM, gerenciador de pacotes do Node.js instalado.

- Instale o angularCLI com `npm install @angular/cli`

- Instale as depend�ncias do projeto com `npm install`

- O servidor serve os arquivos criados a partir da build do Angular, ent�o no terminal
execute: `ng build`

- E rode a aplica��o com `node server.js`

Para acessar abra no navegador o endere�o: `localhost:3000`
