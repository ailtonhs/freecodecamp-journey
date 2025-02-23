# Como let e const funcionam de forma diferente quando se trata de declaração, atribuição e reatribuição de variáveis?

Ao trabalhar com JavaScript, você frequentemente declarará variáveis para armazenar dados que planeja usar em todo o seu programa.

No JavaScript moderno, let e const são as formas preferidas de declarar variáveis, mas diferem na forma como lidam com atribuição e reatribuição de valores.

A let palavra-chave permite que você declare variáveis que podem ser atualizadas ou reatribuídas mais tarde. Você pode pensar nisso let como um contêiner flexível, uma vez que você armazenou um valor nele, você pode alterar esse valor conforme necessário em todo o seu programa.

Aqui está um exemplo de declaração e atribuição de uma variável com let:

let score = 10;

Neste caso, a variável score é declarada e recebe o valor 10. Se você quiser atualizar o valor mais tarde, você pode facilmente fazer isso:

score = 20;

Agora, score mantém o valor 20. Isso é particulamente útil quando você sabe que o valor de uma variável mudurá conforme seu programa é executado.

Por outro lado, const é usado para declarar variáveis que são constantes. Uma vez que você atribui um valor a uma variável declarada com const, você não pode reatribuí-la.

Isso é const, ideal para valores que você não deseja alterar acidentalmente durante a execução do seu programa.

Aqui está um exemplo de declaração e atribuição de uma variável com const:

const maxScore = 100;

Uma vez maxScore atribuído o valor 100, ele não pode ser alterado:

maxScore = 200; //Isso resultará em um erro

Tentar reatribuir um valor a uma const variável gerará um erro no seu console JavaScript, pois const as variáveis são imutáveis depois de atribuídas.

Você pode declarar uma let variável sem atribuir um valor imediatamente a ela, e pode atribuir um valor a ela mais tarde:

let age;
age = 25;

Variáveis declaradas com const devem receber um valor no momento da declaração. Se vocẽ tentar declarar uma const variável sem atribuir um valor a ela, você obterá um erro:

const age; //erro

Você deve usar let quando precisar declarar variáveis que serão reatribuídas mais tarde. Por exemplo, rastrear uma pontuação alterada ou atualizar um valor ao longo do tempo em seu programa.

Use const quando quiser declarar variáveis que devem permanecer constantes, como valores de configuração ou configurações que não devem ser alteradas acidentalmente.

Você também pode usar var palavra-chave, mais não é mais tão recomendado. O var é parecido com let, exceto que tem um escopo mais amplo, o que tem mais probabilidade de causar problemas no seu programa.