## Materiais a serem assistidos previamente
[Gerando dados falsos para testes](https://www.youtube.com/watch?v=hmDcbsrmzF4)
[GManipulando arrays](https://www.youtube.com/watch?v=MXmChiKN4Q4)


## Pré requisitos (Dependências)

[ESLint](https://eslint.org/) - Code style AirBnB

[Editor Config for VSCode](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)

[Faker](https://github.com/marak/Faker.js/)

## Cenário

Tratar o conteúdo de um array com 1.000 registros através de <code> map, filter, reduce e find </code> funções.

Campos dos objetos objetos que irão compor o array: <code> name, birthday, genre, lastpurchase, countpurchase </code>

## Desafios

0. Mockar a criação dos objetos respeitando os seguintes requisitos:
- Os dados devem estar em pt_BR;
- Os dados devem ser coerentes com os seus campos. Ex: é impossível que algum cliente tenha nascido em 2022;
- As datas de nascimento devem ser entre 1910 a 2019.
- Os nomes devem ser nomes completos.

1. Desenvolva, utilizando <code> filter </code>, uma função que, dado um caractere de entrada, retorne todos os registros de clientes cujo o nome inicia com o caractere.

2. Retorne o array de clientes 

3. Desenvolva uma função que, dado o caractere de entrada, retorna apenas um número com o total de registros encontrados.

4. Desenvolva uma função que retorne apenas os nomes dos clientes.

5. Desenvolva uma função que retorne apenas o primeiro nome dos clientes.

6. Desenvolva uma função que retorne apenas o primeiro nome dos clientes cujo os nomes começam com o caractere de entrada da função.

7. Desenvolva uma função que retorne todos os usuários que são maiores de idade.

8. Desenvolva uma função que, dado um nome de entrada, retorna se o nome está contido na lista.

9. Implemente uma função que retorna o total de vendas realizadas somando as compras de todos os clientes.

10. Implemente uma função que retorne os dados dos clientes que não compram há mais de 1 ano.

11. Implemente uma função que retorne os dados dos clientes que já realizaram mais de 15 compras.
