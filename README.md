# Doc_Backend
Ctrl + c = parar terminal
Criando um arquivo para back end

- npm init
  Então começa a pedir as informações dos projetos
  Nome da pasta
  versão
  Descrição            
  entry point
  test command
  git reposytory
  keywords
  autor
  licença
  E dps pede pra confirmar

  instalar express
  npm i --save express
  npm i --save cors (para poder o  front puxar requisiçoes do back-end. Aquela questão de segurança do navegador)

após a instalação criamos o arquivo app.js e passamos o require do express
Depois criamos no script "prod": "node app.js" assim podemos ver a aplicação


npm run prod: para iniciar a aplicação e enviar para produção
Porém dessa forma é necessário derrubar a aplicação

"dev": "nodemon --inspect app.js" dessa forma não é necessário derrubar a aplicação para ver
npm run dev





  
