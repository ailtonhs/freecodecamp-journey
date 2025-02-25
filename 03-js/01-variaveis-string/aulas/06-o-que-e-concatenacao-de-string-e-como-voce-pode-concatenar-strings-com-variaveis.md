# O que é concatenação de strings e como você pode concatenar strings com variáveis

Em JavaScript, trabalhar com texto é uma parte essencial da codificação e, frequentemente, você precisará combinar ou juntar pedaços de texto. Esse processo é chamado de concatenação de strings.

Nesta aula, vamos nos concentrar em como a concatenação de strings funciona, especificamente usando o operador +, o operador += e o concat() método.

O + operador é um dos métodos mais simples e mais frequentemente usados para concatenar strings. Ele permite que você junte várias strings ou combine strings com variáveis que contenham texto.

Aqui está um exemplo:

let firstName = "Jhon";
let lastName = "Doe";

let fullName = firstName + " " + lastName;

Nesse exemplo, usamos o + operador para concatenar as variáveis firstName e lastName junto com um espaço (" ") para criar o nome completo.

Uma desvantagem de usar o + operador para concatenação de strings é que isso pode levar a problemas de espaçamento se você não gerenciar cuidadosamente o espaçamento entre as strings concatenadas.

Aqui est´a um exemplo onde um espaço está faltando:

let firstName = 'John';
let lastName = 'Doe';
let fullName = firstName + lastName; //JohnDoe

Sempre que você usar o + operador para concatenar strings, é importante verificar novamente se há possíveis problemas de espaçamento.

Se você precisar adicionar ou anexar a uma string existente, então você pode usar o operador +=. Isso é útil quando você quer construir sobre uma string adicionando mais texto a ela ao longo do tempo.

Aqui está um exemplo de comoo anexar uma string a outra usando o operador +=:

let greentig = 'Hello';
greentig = ', John!';

É importante lembrar que strings são imutáveis, o que significa que, depois que uma string é criada, você não pode alterá-la.

Neste caso, a sequência original de Hello não é modificada. Em vez disso, a saudação agora faz referência à nova sequência de Hello, John!.

Outra maneira de concatenar strings é usar o concat() método.

Antes de começarmos a aprender sobre o concat() método, é importante primeiro entender o que são um método e uma função em um nível mais alto.

Em programação, uma função é um bloco de código reutilizável que executa uma tarefa específica e pode ser chamada com várias entradas. Um método, por outro lado, é um tipo de função que é associada a um objeto, o que significa que opera nos dados contídos naquele objeto.

Aqui está um exemplo de uso do concat() método para unnir duas strings:

let str1 = 'Hello';
let str2 = 'World';

let result = str1.concat(' ', str2);

Neste exemplo, usamos o concat() método para unir str1, um espaço(' ') e str2 em uma única string.

Para concluir, o operador + é melhor para concatenação simples, especialmente quando você precisar combinar algumas strings ou variáveis.

O operador += é útil ao criar um string passo a passo ou ao acrescentar novo conteúdo a uma variável de string existente.

Por fim, o método concat() é benéfico quando você precisa concatenar várias strings.