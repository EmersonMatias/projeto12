*************** POST SIGN-UP ******************
1. Verifica se o URL é valido
    a) Caso não seja, ele não permite a criação da conta
2. Verifica se o campo do username é vazio
    a) Caso esteja, ele não permite a criação da conta


*************** POST TWEETS ******************
1. Verifica se o usuario tem conta criada
    a) Caso não tenha, ele não permitira a publicação de tweets
2. Verifica se o tweet é vazio
    a) Caso seja, ele não permite a publicação do tweet
3. Verifica se o username enviado no body é vazio
    a) Caso seja, ele não permite a publicação do tweet

*************** GET TWEETS ******************
1. Retorna os ultimos 10 tweets da lista de todos os tweets


*************** TESTES ******************
1. Caso você tenha criado a conta uma vez é possivel entrar novamente
apenas pelo username, sem a necessidade da URL da imagem. No entanto,
não é possível alterar a imagem posteriormente.


