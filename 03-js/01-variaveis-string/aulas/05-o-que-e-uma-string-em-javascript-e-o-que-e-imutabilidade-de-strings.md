# O que é uma string em JavaScript e o que é imutabilidade-de-strings?

Em JavaScript, uma string é uma sequência de caracteres usada para representar dados de texto. Strings são um dos tipos de dados primitivos na linguagem, Junto com números, boolean, null e undefined.

Para criar uma string em JavaScript, você pode usar aspas simples(') ou aspas duplas(").

Aqui está um exemplo de criação de duas variáveis que contêm valores de strings:

let singleQuotes = 'This is a string';
let doubleQuotes = "This is also a string";

Embora você possa usar aspas simples ou duplas para criar strings, é importante ser consistente. Se uma string começa com uma aspa simples, ela também deve terminar com uma aspa simples.

O mesmo se aplica a aspa duplas. O exemplo a seguir lançará um erro porque começa com aspas duplas e termina com aspas simples:

const improperStr = "Doe not do this';

Outra coisa a levar em conta é que strings são imutáveis. Em programação, imutabilidade significa que uma vez que algo é criado, não pode ser alterado. Então, quando você criar uma string, não pode alterar seus caracteres diretamente. Em vez disso você criaria uma nova string se quisesse fazer alterações.

Aqui está um exemplo de atribuição de uma nova string a uma variável developer:

let developer = "Jessica";
developer = "Quincy";

Como strings são imutáveis, não podemos atualizar a primeira string diretamente. É por isso que estamos atribuindo uma nova string à variável developer.