# Challenge RecargaPay
## https://jsonplaceholder.typicode.com/ API tests with Postman

Projeto desenvolvido por **Ricardo Moura**

## Descrição
Foram criados dois steps de teste para o resource /posts, um para o metodo GET e outro para POST

As validações incluem:

- HTTP status

- Existência do cookie do cloudflare

- Existência de todos os Headers 

- Valor de Header comparando com String

- Valor de Header utilizando REGEX

- Schema do Body da response

- Quantidade de objetos no array

- Comparação dos valores da resposta com os enviados na request

## Observações
O projeto de teste foi desenvolvido considerando que as responses enviadas estão corretas, portanto foram utilizadas algumas comparações com strings fixas, entendo que a resposta deve ser completamente validada, Headers e Payload, porém é necessária uma documentação um pouco mais detalhada da API para melhor exploração das possibilidades de teste.

Ficarei muito feliz em conversarmos melhor sobre o projeto e a possibilidades de teste.
