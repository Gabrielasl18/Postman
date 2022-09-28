# Postman
> Permite aos usuários criar e salvar solicitações HTTP e HTTPs simples e complexas, bem como ler suas respostas. Com ele é possível consumir facilmente serviços locais e na internet, enviando dados e efetuando testes sobre as respostas das requisições. Por fim, essa ferramenta da suporte à documentação das requisições feitas pela API. Ele possui ambiente para a documentação, execução de testes de APIs e requisições em geral.

* Realizar requisições para APIs;
* Fazer testes automatizados.

## Coleções
> Cada coleção agrupa as requisições (como se fossem pastas). Podem ser executadas separadas ou todas de uma vez.

## Requisição
> Cada requisição tem os dados da requisição e a tela de resposta.

<i>Tipos de requisições no Postman</i>

* Get
* Post
* Put
* Delete

<dl>
    <dt><strong>get</strong></dt>
    <dd>É a requisição mais básica e a mais utilizada, pois a partir dela conseguimos recuperar os dados presentes na API de forma simples.<dd>
    <dt><strong>post</strong></dt>
    <dd>Vamos usar sempre que precisarmos inserir novos dados na API, porque é com ele que indicamos os valores que iremos adicionar.</dd>
    <dt><strong>put</strong></dt>
    <dd>É a requisição responsável por modificar os dados da API. Para realizá-la precisamos(novamente) mudar o tipo de requisição e declarar a URL. No entanto, com um pequeno diferencial: precisamos também definir qual dado iremos modificar e só então passamos o id referente.</dd>
    <dt><strong>delete</strong></dt>
    <dd>É responsável por deletar um valor na API. Para realizar essa requisição, precisamos modificar o tipo da requisição e definir qual id do registro iremos remover.</dd>
</dl>
