# Projeto 12 - API Tweteroo (Driven)
Tweteroo é um projeto de API que replica algumas funcionalidades do Twitter. Este projeto foi desenvolvido como um exercício de construção de um back-end completo para uma aplicação front end.

🟡Nessa aplicação os dados do usuário são salvos em variáveis globais em memória, ou seja, eles não persistem caso o servidor encerrar.

#### Formato do ```user```

```javascript
  {
    username: "nome_do_usuario",
    avatar: "url_image_avatar"
  }
```
#### Formato do ```tweet```

```javascript
  {
    username: "nome_do_usuario",
    tweet: "tweet do usuario"
  }
```

#### 🟠 POST ```/signup```
* Recebe pelo body um objeto do tipo ```user``` e valida se os valores não estão vazios, caso esteja, retornará ```status code 404```, caso não esteja salva o user em um array de usuários do servidor.
* Response: ```"OK"```

#### 🟠 POST ```/tweets```
* Recebe pelo body um objeto do tipo ```tweets``` e valida se os valores não estão vazios, caso esteja, retornará ```status code 404```, caso não esteja salva o tweet em um array de tweets do servidor.
* Response: ```"OK"```

#### 🟢 GET ```/tweets```
* Retorna os 10 últimos tweets publicados
```javascript
  [
	{
		username: "bobesponja",
			"vatar: "https://super.abril.com.br/wp-content/uploads/2020/09/04-09_gato_SITE.jpg?  quality=70&strip=info",
		  tweet: "eu amo o hub"
	}
]
```

### As principais tecnologias e conceitos aplicados nesse projeto incluem:
* Node.js
* Express.js
