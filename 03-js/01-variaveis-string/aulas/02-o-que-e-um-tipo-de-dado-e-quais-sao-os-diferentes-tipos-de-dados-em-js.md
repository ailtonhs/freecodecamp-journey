# O que é um tipo de dado e quais são os diferentes tipos de dados em JavaScript?

Em JavaScript, um tipo de dado se refere ao tipo de valor que uma variável contém.

Uma Variável é um contêiner nomeado que armazena um valor de um tipo de dado específico, permitindo que você o referencie e manipule em todo o seu código. Os tipos de dados ajudam o programa a entender o tipo de dado com o qual está trabalhando, seja um número, texto ou outra coisa

O JavaScript tem vários tipos básicos de dados que você usará em seus programas.

## Tipo de dado Number

A Number representa inteiros e valores de ponto flutuante. Exemplos de inteiros incluem 7, 19, e 90. Exemplos de números de ponto flutuante incluem 3.14 e 5.2. Um números de ponto flutuante é um número com um ponto decimal.

## Tipo de dado String

A String é uma sequência de caracteres, ou texto, entre aspas. Aqui estão dois Exemplo:

* "Olá, Mundo!"
* 'JavaScript'

## Tipo de dado Boolean

A Boolearn representa um de dois valores possíveis: true ou false. Você pode usar um booleano para verificar se uma página está carregando, ou se um usuário está logado ou não.


## Tipo de dado Undefined e Null

Undefined significa que uma variável foi declarada, mas ainda não recebeu um valor. Null significa que a variável foi intencionamente definida como "nada" e não contém nenhum valor.

## Tipo de dado Object

A Object é um tipo de dado mais complexo que pode conter coleções de pares de chave-valor. Vamos decompô-lo. A chave(também chamada de nome de propriedade) é como um rótulo para os dados, enquanto o valor são os dados reais que você deseja armazenar. Aqui está um exemplo:

let pessoa = {
    nome: 'Pedro',
    idade: 22
};

Cada par chave-valor em um objecto é chamado de propriedade. Então podemos dizer que este objeto de pessoa tem duas propriedades. 

## Tipo de dado Symbol e BigInt

A Symbol é um tipo especial de valor em JavaScript que é sempre único e não pode ser alterado. É frequentemente usado para criar rótulos ou identificadores exclusivos para propriedades:

const symbol1 = Symbol('mySymbol');
const symbol2 = Symbol('mySymbol');
console.log(symbol1 === symbol2); //false

Neste exemplo, criamos dois símbolos com a mesma descrição, mas eles são únicos.

BigInt é usado para números muito grande que excedem o limete do Number tipo:

const bigNumber = 1234567890123456789012345678901234567890n;

Neste exemplo, criamos um BigInt adicionando n no final de um número muito grande.




