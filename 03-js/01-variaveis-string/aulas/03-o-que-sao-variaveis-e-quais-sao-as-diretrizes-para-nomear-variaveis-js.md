# O que são variáveis e quais são as diretrizes para nomear variáveis JavaScript

Em JavaScript, as variáveis funcionam como contêineres para armazenar dados que você pode acessar e modificar em todo o seu programa.

Você pode pensar em variáveis como caixas que guardam valores. Com variáveis, você pode manter o controle de coisas como números ou texto e consultar esses valores sempre que precisar deles em seu programa.

Uma maneira de declarar uma variável em JavaScript é usar a let palavra-chave. 

Aqui está um exemplo de uso let para declarar uma variável chamada age:

let age;

No momento, a age variável não tem um valor atribuído a ela. Para atribuir um valor a uma variável, você precisará usar o operador de atribuição como este:

let age = 25;

O operador de atribuição parece um sinal de igual(=), mas não verifica a igualdade. O operador de atribuição é usado para atribuir um valor a uma variável. Esse processo de atribuição de um valor a uma variável é conhecido comoo inicialização.

Uma vantagem de usar a let palavra-chave para declarar variáveis é que você pode reatribuir valores a elas. Em programação significa dar um novo valor a uma variável que já tem um.

Aqui está um exemplo de reatribuição do valor age variável:

age = 30;

Agora a age variável contém o valor 30. Observe que a let palavra-chave não foi necessária novamente porque a age variável já foi declarada, então não há necessidade de declará-la uma segunda vez.

Ao usar a reatribuiçã, vocẽ só precisa referenciar o nome da variável. A reatribuição é útil porque permite que você atualize e altere o valor armazenado em uma variável conforme seu programa é executado. Um bom exemplo disso seria atualizar pontos em um jogo.

Nomear variáveis pode parecer simples, mas existem algumas regras e práticas recomendadas para garantir que seu código seja legível e funcional.

Os nomes das suas variáveis devem descrever o que os dados representam. Por exemplo, em vez de usar um nome como x, um nome mais descritivo como age ou points tornaa seu código mais fácil de entender.

variáveis em JavaScript devem começar com uma letra, um sublinhado(_) ou um cifrão($). Elas não podem começar com número.

Os nomes de variáveis diferenciam maiúsculas de minúsculas, o que significa que a palavra age toda em minúsculas e a palavra Age são consideradas variáveis diferentes.

É por isso que é importante manter uma convenção de nomenclatura consistente, como camelCase. CamelCase é onde a primeira palavra é toda em minúscula e cada palavra subsequente começa com uma letra maiúscula.

Aqui está um exemplo de uso da convenção de nomenclatura camelCase para uma variável:

let thisIsCamelCase;

Existem certas palavra-chave em JavaScript que você não pode usar como nomes de variáveis, com let, const, function, ou return, pois elas são reservadas para a própria linguagem.

Você também deve evitar usar caracteres especiais como pontos de exclamação(!) ou símbolos de arroba(@), em seus nomes de variáveis. É mehor manter os nomes de variáveis legíveis usando letras, números, sublinhados ou cifrões.