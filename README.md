# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 


## Conteúdo Técnico
Escreva aqui os conteúdos aprendidos.



## Atividades desenvolvidas
Escreva aqui as atividades desenvolvidas em sala e para casa. Você pode detelhar a atividade e usar links das atividades do codepen e vídeos desenvolvidos em sala. 


## Vanessa Raquely 

- Em primeiro passo desenvolvemos e aprendemos a ultilizar o code pen e as linguagens e variáveis do javascript.

- Em JavaScript, existem três tipos de variáveis ​​diferentes: var, let, e const. Cada uma dessas variáveis ​​tem várias regras sobre como devem ser usadas e têm características diferentes.

## var

"var" é uma palavra-chave usada para declarar variáveis. Ao contrário de "let" e "const", variáveis declaradas com "var" têm escopo de função ou escopo global e não têm escopo de bloco. 
Isso significa que uma variável declarada com var dentro de um bloco, como um if ou for, estará acessível fora desse bloco.

## Características do var:

*Escopo de função: Se declarada dentro de uma função, só está acessível dentro dessa função.

*Escopo global: Se declarada fora de qualquer função, está acessível globalmente.

*Hoisting: Variáveis declaradas com var são "movidas" para o topo do seu escopo durante a compilação. No entanto, elas são inicializadas com undefined até sua atribuição.
Pode ser redeclara no mesmo escopo, o que pode causar confusão.

exemplo:

var nome = "João";
console.log(nome); // João

nome = "Maria"; // Atualizando a variável
console.log(nome); // Maria

 *A variável nome é declarada usando a palavra-chave var e recebe o valor "João".
 
 *console.log(nome); para exibir o valor da variável nome, que no momento é "João".
 
 *Em seguida, a variável nome é reatribuída com o valor "Maria". Como var permite que o valor de uma variável seja alterado, isso é possível sem problemas.
 
 *Finalmente, usamos console.log(nome); novamente para exibir o novo valor da variável nome, que agora é "Maria".


## let

 "let" é uma palavra-chave usada para declarar variáveis com escopo de bloco, instrução ou expressão. Isso significa que a variável só é acessível dentro do bloco onde foi declarada. 

O let é diferente da palavra-chave var, que define uma variável globalmente ou no escopo inteiro de uma função. 

## características do let: 

*A variável let pode ser atualizada, mas não pode ser declarada novamente. 

*A palavra-chave let não é inicializada, ao contrário da var, que é inicializada como undefined. 

*Se tentar usar uma variável let antes de sua declaração, terá um Reference Error. 

*O let evita problemas de escopo indesejados que podem ocorrer com o uso de var. 

exemplo:

let var1 [= value1] [, var2 [= value2]] [, ..., varN [= valueN]];

## const

 "const" é uma palavra-chave usada para declarar variáveis que não podem ser reatribuídas. 
 Isso significa que uma vez que uma variável é declarada com const, seu valor não pode ser alterado. 
 No entanto, se a variável for um objeto ou um array, seus elementos internos podem ser modificados.

## Características do const:

*Imutabilidade da referência: Você não pode reatribuir a variável, mas pode modificar o conteúdo se for um objeto ou array.

*Escopo: const tem escopo de bloco, o que significa que a variável é visível apenas dentro do bloco onde foi definida.

*Inicialização obrigatória: Você deve inicializar a variável ao declará-la

exemplo:

const pi = 3.14;
// pi = 3.14159; // Isso causaria um erro: TypeError: Assignment to constant variable.
console.log(pi); // Saída: 3.14


