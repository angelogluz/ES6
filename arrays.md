## Materiais de apoio
[Gerando dados falsos para testes](https://www.youtube.com/watch?v=hmDcbsrmzF4)

[Arrow functions](https://www.youtube.com/watch?v=ihWA4tri1Fc)

[Manipulando arrays](https://www.youtube.com/watch?v=MXmChiKN4Q4)


## Pré requisitos (Dependências)

[Faker](https://fakerjs.dev/guide/)

## Cenário

Tratar o conteúdo de um array com 1.000 registros através de <code> map, filter, reduce e find </code> funções.

Campos dos objetos objetos que irão compor o array: <code> name, birthday, genre, lastPurchaseDate, countPurchase </code>

## Desafios

0. Mockar a criação dos objetos respeitando os seguintes requisitos:
- Os dados devem estar em pt_BR;
- Os dados devem ser coerentes com os seus campos. Ex: é impossível que algum cliente tenha nascido em 2022;
- As datas de nascimento devem ser entre 1910 a 2019.
- Os nomes devem ser nomes completos.

1. Desenvolva, utilizando <code> filter </code>, uma função que, dado um caractere de entrada, retorne todos os registros de clientes cujo o nome inicia com o caractere.

2. Liste os nomes dos clientes no padrão: "Cliente: NOME_DO_CLIENTE"

3. Liste os nomes dos clientes no padrão: "Cliente INDEX: NOME_DO_CLIENTE".

4. Desenvolva uma função que, dado o caractere de entrada, retorna apenas um número com o total de registros encontrados.

5. Desenvolva uma função que retorne apenas os nomes dos clientes.

6. Desenvolva uma função que retorne apenas o primeiro nome dos clientes.

7. Desenvolva uma função que retorne apenas o primeiro nome dos clientes cujo os nomes começam com o caractere de entrada da função.

8. Desenvolva uma função que retorne todos os usuários que são maiores de idade.

9. Desenvolva uma função que, dado um nome de entrada, retorna se o nome está contido na lista.

10. Implemente uma função que retorna o total de vendas realizadas somando o total de compras de todos os clientes.

11. Implemente uma função que retorne os dados dos clientes que não compram há mais de 1 ano.

12. Implemente uma função que retorne os dados dos clientes que já realizaram mais de 15 compras.

13. Desenvolva uma função receba como entrada um número, que representa um ano, e retorne o total de itens vendidos no ano de entrada.


## Exercícios diversos

1. Função que receba um cliente e adicione no INICIO do array de clientes.
2. Pegar e imprimir somente o nome e o total de compras do primeiro cliente cliente da lista
3. Separar o nome cliente[0] do resto do objeto
4. Desenvolva uma função que some N valores de entrada
