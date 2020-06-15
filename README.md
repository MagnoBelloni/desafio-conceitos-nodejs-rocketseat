# desafio-conceitos-nodejs-rocketseat
<h3>Desafio do Bootcamp GoStack 11 da Rocketseat.</h3>

Back-end de uma Aplicação para armazenar repositórios do seu portfólio, que irá permitir a criação, listagem, atualização e remoção dos repositórios, e além disso permitir que os repositórios possam receber "likes".

<h2>Para rodar a aplicação</h2>
<ol>
  <li>Execute "yarn" no terminal para instalar todas as dependencias.</li>
  <li>Execute "yarn dev", para rodar a aplicação, ela ficara no endereço "http://localhost:3333/"</li>
</ol>

<h2>Para rodar os testes</h2>
<ol>
  <li>Execute "yarn" no terminal para instalar todas as dependencias.</li>
  <li>Execute "yarn test" para rodar os testes.</li>
</ol>

<h2>Rotas</h2>
<ul>
  <li><b>POST /repositories:</b> A Rota deve receber title, url e techs dentro do corpo da requisição, sendo a URL o link para o github desse repositório.</li>
  <li><b>GET /repositories:</b> A rota que lista todos os repositórios.</li>
  <li><b>PUT /repositories/:id:</b> A rota altera apenas o title, a url e as techs do repositório que possua o id igual ao id presente nos parâmetros da rota.</li>
  <li><b>DELETE /repositories/:id:</b> A rota deleta o repositório com o id presente nos parâmetros da rota.</li>
  <li><b>POST /repositories/:id/like:</b> A rota deve aumentar o número de likes do repositório específico escolhido através do id presente nos parâmetros da rota, a cada chamada dessa rota, o número de likes deve ser aumentado em 1.</li>
</ul>
