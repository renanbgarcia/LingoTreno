# LearnQuotes

Esse � um projeto que eu fiz para come�ar a aprender Angular e typescript.
� um web aplicativo que gera cita��es aleat�rias. Eu deixei dispon�vel
duas op��es de linguas para as cita��es, ingl�s e franc�s.

Eu usei a API do MediaWiki para obter dados do WikiQuotes.
Os dados retornados da API, assim como � referenciado na documenta��o dela, n�o
s�o sem�nticos. Ou seja, foi bem complicado conseguir obter os dados necess�rio corretamente
para poder chegar � uma cita��o formatada. Mas eu consegui chegar a um resultado razo�vel
com os dados vindos da API em ingl�s e franc�s. Ainda � poss�vel conseguir o mesmo com outras
l�nguas.

## Como rodar

Para ver o app em funcionamento baixe ou clone o reposit�rio.

Voc� vai precisar ter o NPM, gerenciador de pacotes do Node.js instalado.

Instale o angularCLI com `npm install @angular/cli`

Instale as depend�ncias do projecto com `npm install`

E rode a aplica��o com `ng serve` ou `npm start`

Por padr�o a aplica��o estar� rodando na porta 4200. Para acessar abra no navegador o endere�o:

`localhost:4200`