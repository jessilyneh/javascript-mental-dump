# Objetos
Tudo são objetos. Menos tipos primitivos.
Arrays, RegEx, Dates e outros valores não primitivos.

```javascript
// Date
console.log(typeof(new Date())); //object
// RegEx
console.log(typeof(/\w/)); //object
// Objeto
console.log(typeof({})); //object
// Array
console.log(typeof([])); //object
// Math, para calculos matemáticos
console.log(typeof(Math)); //object
```

Uma das coisas que diferencia objetos de tipos primitivos é que objetos são mutáveis, pois podemos acessar e modificar as propriedades de um objeto usando . ou [ ] .

```javascript
let fruit = { name: 'orange' };
fruit['name'] = 'orange'; // notação de chaves
fruit.name = 'orange'; // notação de ponto
```

Diferente de tipos primitivos, que não podem ser "criados" novos tipos primitivos, podemos criar objetos. Você também pode criar arrays, Dates e todos os demais tipos de objetos.

```javascript
const fruit = {}
```

## Construtores e protótipos

JavaScript é uma linguagem multiparadigma que se baseia em protótipos,diferente de linguagens que usam classes e são orientadas a objetos, como Java. Apesar de ser possível usar orientação a objetos em Javascript, também é possível usar outros paradigmas de programação, logo, é mais correto afirmar que é multiparadigma, mas não é errado afirmar que Javascript é uma linguagem para trabalhar com Orientação a Objetos - só é uma resposta incompleta.