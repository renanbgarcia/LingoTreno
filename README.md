# LearnQuotes

Esse � um projeto que eu fiz para come�ar a aprender Angular e typescript, al�m de fundamentos de Back-End com
Node.js e express.js, criando uma REST API que serve o back-end do aplicativo.

Eu comecei tentando fazer um web aplicativo que gera cita��es aleat�rias, agora estou tentando
expandir as funcionalidades para fazer um aplicativo de aprendizagem de idiomas usando a gera��o de
cita��e sem diversas l�nguas.

Atualmente j� foi criado:

1. Login utilizando a estrat�gia Google OAuth do Passport.js.
2. Gera��o de cita��es aleat�rias em Ingl�s e Franc�s.
3. Roteamento das p�ginas. (o roteamento do front-end � feito usando o Angular).
4. Conex�o com banco de dados(MongoDB)para gerenciamento de usu�rios (algumas rotas da API j� est�o funcionando).

TODO:

1. Construir perfil do usu�rio.
2. Adicionar um dicion�rio usando Wiktionary.
3. Criar funcionalidade para facilmente marcar palavras aprendidas.
4. Adicionar m�todos de estudo/revis�o de cita��es/palavras aprendidas.
5. Consertar toda a parte de typescript :<
6. etc etc etc

Eu usei a API do MediaWiki para obter dados do WikiQuotes.
Os dados retornados da API, assim como � referenciado na documenta��o dela, n�o
s�o sem�nticos, ou seja, foi bem complicado conseguir obter os dados necess�rio corretamente
para poder chegar � uma cita��o formatada. Mas eu consegui chegar a um resultado razo�vel
com os dados vindos da API em ingl�s e franc�s. Ainda � poss�vel conseguir o mesmo com outras
l�nguas.

## Como rodar

(s� a gera��o de cita��es)
Acesse online no endere�o: https://renanbgarcia.github.io/learnquotes/

Ou rode localmente:

- Baixe ou clone o reposit�rio.

- Voc� vai precisar ter o NPM, gerenciador de pacotes do Node.js instalado.

- Instale o angularCLI com `npm install @angular/cli`

- Instale as depend�ncias do projeto com `npm install`

- O servidor serve os arquivos criados a partir da build do Angular, ent�o no terminal
execute: `ng build`

- E rode a aplica��o com `node server.js`

Para acessar abra no navegador o endere�o: `localhost:3000`
