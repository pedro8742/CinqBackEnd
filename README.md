Cinq-Back END
Este repositório utiliza as dependências Express e Sequelize.

É necessário criar um banco de dados para poder ser realizada a autenticação com o sequelize.

1º Passo - Iniciar NPM
Acesse o terminal e execute o seguinte comando para iniciar o NPM e suas dependências.

npm install

2º Passo - Conexão com Banco de Dados pelo Sequelize
No Arquivo .env insira os dados do seu banco nos respectivos espaços:

DB_NAME=cinq
DB_USER=root
DB_PWD=123
DB_HOST=localhost
DB_PORT=3306
DB_DIALECT=mysql
NODE_ENV=development

3º Passo - para criar o banco pela primeira vez coloque o código abaixo:
npx sequelize-cli db:migrate
