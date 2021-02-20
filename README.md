<h1>API SOLID</h1>

API construída seguindo o video da Rocketseat:
https://www.youtube.com/watch?v=vAV4Vy4jfkc&t=10s

Aplicação de criação de usuário e envio de email utilizando os principais conceitos de SOLID.

Para utilizar a API basta realizar os seguintes comandos:

<h3>yarn install</h3>
<h3>yarn start</h3>

Após isso criar request do tipo POST, via Insomnia ou Postman, para a rota: http://localhost:3333/users

Exemplo de conteudo do Body/Json:
{
	"name": "Nome",
	"email": "email@email.com",
	"password": "senha"
}
