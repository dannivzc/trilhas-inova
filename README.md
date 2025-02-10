# Resolução dos Desafios do Programa : Trilhas Inova Maranhão 2B

### Desafio 1 resolvido:

1. Crie uma variável chamada nome e atribua seu nome a ela. Em seguida, exiba o valor dessa variável.

```js
let nome = "Danniella";
console.log(nome); 
```
2. Crie duas variáveis: uma chamada idade e outra chamada altura. Atribua a idade o valor 25 e a altura o valor 1.75. Exiba ambos os valores.
```js
let idade = 25;
let altura = 1.75;
console.log(idade, altura); 
```
3. Crie uma variável chamada preco com o valor 50 e uma variável desconto com o valor 0.2 (20%). Calcule o preço com desconto e exiba o valor final.
```js
let preco = 50;
let desconto = 0.2;
let precoComDesconto = preco - (preco*desconto); 
console.log(precoComDesconto);
```
4. Crie uma variável chamada temperatura e atribua o valor 30. Se a temperatura for maior que 25, exiba a mensagem "Está calor!". Caso contrário, exiba "Está fresco!".
```js
let temperatura = 30;
if (temperatura > 25) {
    console.log('Está calor!');
} else {
    console.log('Está fresco!');
}
```
5. Crie uma variável idade e atribua um valor. Se a pessoa for maior de idade (18 ou mais), exiba "Você é maior de idade". Caso contrário, exiba "Você é menor de idade".
```js
let idade = 19;
if (idade >= 18) {
    console.log('Você é maior de idade');
} else {
    console.log('Você é menor de idade');
}
```
6. Crie uma variável chamada nota e atribua um valor entre 0 e 10. Se a nota for maior ou igual a 7, exiba "Aprovado". Se for entre 5 e 6, exiba "Recuperação". Caso contrário, exiba "Reprovado".
```js
let nota = 8;
if (nota >= 7) {
    console.log("Aprovado");
} else if (nota >= 5) {
    console.log("Recuperação");
} else {
    console.log("Reprovado");
}
```
7. Crie duas variáveis, numero1 e numero2, e atribua valores a elas. Verifique se os dois números são iguais e, caso sejam, exiba "Os números são iguais". Caso contrário, exiba "Os números são diferentes".
```js
let numero1 = 5;
let numero2 = 10;
if (numero1 == numero2) {
    console.log("Os números são iguais");
} else {
    console.log("Os números são diferentes");
}
```
8. Crie uma variável chamada nome e uma variável chamada idade. Exiba a mensagem "Olá, meu nome é [nome] e eu tenho [idade] anos", utilizando concatenação.
```js
let nome = "Danniella";
let idade = 19;
console.log("Olá, meu nome é " + nome + " e eu tenho " + idade + " anos");
```
9. Crie um loop que imprima os números de 1 a 10 na tela.
```js
let contador = 1;
while(contador <= 10) {
    console.log(contador);
    contador++;
}
```
10. Crie um loop que peça ao usuário para digitar um número até que ele digite o número 5.
```js
let numero;
while(numero != 5)  {
    numero = parseInt(prompt('Digite um número:'));
    console.log('Você digitou o número 5. Programa encerrado!');
} 
```
11. Crie um loop que imprima a tabuada do número 7, de 1 a 10.
```js
let multi = 1;
let numero = 7;

while(multi <= 10) {
    let resultado = numero * multi;
    console.log(`${numero} x ${multi} = ${resultado}`);
    multi++;
}
```
12. Crie um loop que exiba todos os números pares de 0 a 20.
```js
let numerosPares = 0
while(numerosPares <= 20) {
    console.log(numerosPares);
    numerosPares += 2;
}
```
13. Escreva um código que calcule a área de um círculo. Utilize uma função para realizar o cálculo. A função deve receber o raio como parâmetro e retornar a área.
```js
function calcularAreaCirculo(raio) {
    let area = Math.PI * raio * raio; // Vi o Math.PI sendo utilizado em um dos exercicios resolvidos pelo instrutor da Alura
    return area;
}
console.log(calcularAreaCirculo(6));
```
14. Comente seu código explicando o que cada parte faz. Crie um programa simples que calcule a soma de dois números e imprima o resultado.
```js
// Função para realizar a soma dos dois números 
function somar (a, b) {
    let soma = a + b; // Calcula a soma dos dois números
    return soma; // Retorna o resultado da soma 
}
let resultado = somar(10, 30); // Variável que recebe o retorno da função
console.log(resultado); // Exibe o resultado
```
15. Refatore o código abaixo para que seja mais legível, usando boas práticas de nomenclatura e separando o código em funções:
```js
x = 10
y = 20
z = x+y
console.log(z)
```
```js
function somarNumeros(x, y) {
    return x + y;
}
let x = 10;
let y = 20;
let z = somarNumeros(x, y);
console.log(z);

