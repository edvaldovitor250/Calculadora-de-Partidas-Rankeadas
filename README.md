# Calculadora-de-Partidas-Rankeadas

![Screenshot_1](https://github.com/edvaldovitor250/Calculadora-de-Partidas-Rankeadas/assets/116117189/dfabf03f-3b8e-4c17-a8b5-c8005a1cd16d)

## Explicação do código a baixo:

1. `let Heroi = "Tuzz";`: Aqui estamos criando uma variável chamada `Heroi` e atribuindo a ela o valor "Tuzz". Essa variável vai armazenar o nome do herói.

2. `let saldoVitorias = saldo();`: Aqui estamos criando uma variável chamada `saldoVitorias` e atribuindo a ela o resultado da função `saldo()`. Essa função vai calcular o saldo de vitórias e derrotas do herói.

3. ```javascript
   function saldo(vitoria = 12, derrotas = 10) { ... }
   ```: Esta é a definição da função `saldo`. Ela aceita dois argumentos: `vitoria` e `derrotas`, mas se nenhum valor for fornecido, os valores padrão são 12 para vitórias e 10 para derrotas. A função retorna a diferença entre o número de vitórias e derrotas, que é o saldo.

4. `let nivel = "";`: Criamos uma variável chamada `nivel` e a inicializamos com uma string vazia. Esta variável será usada para armazenar o nível do herói com base no saldo de vitórias.

5. O código a seguir utiliza estruturas condicionais (`if` e `else if`) para determinar o nível do herói com base no saldo de vitórias. As regras são as seguintes:
   - Se o saldo for menor que 10, o nível é "Ferro".
   - Se o saldo estiver entre 11 e 20, o nível é "Bronze".
   - Se o saldo estiver entre 21 e 50, o nível é "Prata".
   - E assim por diante, até chegar a "Imortal" se o saldo for maior ou igual a 101.

6. `console.log(...)`: Por fim, usamos `console.log` para exibir uma mensagem no console do navegador ou no ambiente de desenvolvimento. A mensagem informa o saldo de vitórias do herói e o nível em que ele se encaixa, com base nas regras estabelecidas nas estruturas condicionais.

Portanto, o código realiza cálculos e toma decisões com base no saldo de vitórias do herói e, em seguida, exibe uma mensagem que informa o resultado, ou seja, o saldo de vitórias e o nível do herói de acordo com as regras definidas.
