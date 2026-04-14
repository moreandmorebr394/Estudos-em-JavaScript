# Variáveis
São tipo caixas que podem adicionar certas informações. Cada caixa deve ter um nome, mas devem conter o nome relacionado com a informação dessa caixa. Javascript não vai verificar se a informação dentro dessa caixa é equivalente a sua utilização, mas é uma boa prática para a leitura do código.

Entretanto, existe palavras reservadas dentro do JavaScript que não podem ser utilizadas para a criação de uma variável.

Abstract, arguments, await, boolean, break, byte, case, catch, char, class, const, continue, debugger, default, delete, do, double, else, enum, eval, export, extends, false, final, finally, float, for, function, goto, implements, if, import, in, istanceof, int, interface, let, long, native, new, null, package, private, protected, public, return, short, static, super, switch, synchronized, this, throw, throws, transient, true, try, typeof, var, void, volatile, while, with, yield

Tanto let, como var podem ser utilizados para criar variáveis, embora não são a mesma coisa.
Var veio da sintaxe original do JavaScript, já o let foi adicionado depois.

let não permite declarar outra variável com o mesmo nome, já var sim, podendo causar problemas na execução do programa.

Adiciona-se valor a uma variável com = 

O interpretador reconhece o valor e mostra no terminal, mas a mesma palavra com aspas, vai ser interpretado como um texto.

Variáveis em JavaScript são não tipado. Isso quer dizer que o valor adicionado não é controlado. Pode ter começado com um número e facilmente transformado para uma string

let bolsa  =  100;
console.log(bolsa);  //  ->  100
bolsa  =  120;  //  ->  120
console.log(bolsa);
bolsa  =  bolsa  +  200;
console.log(bolsa);  //  ->  320

# Variables
Ce sont comme des boîtes qui peuvent ajouter certaines informations. Chaque case doit avoir un nom, mais elle doit contenir le nom lié aux informations contenues dans cette case. Javascript ne vérifiera pas si les informations contenues dans cette case sont équivalentes à son utilisation, mais c'est une bonne pratique pour lire le code.

Cependant, il existe des mots réservés dans JavaScript qui ne peuvent pas être utilisés pour créer une variable.

Abstract, arguments, await, boolean, break, byte, case, catch, char, class, const, continue, debugger, default, delete, do, double, else, enum, eval, export, extends, false, final, finally, float, for, function, goto, implements, if, import, in, istanceof, int, interface, let, long, native, new, null, package, private, protected, public, return, short, static, super, switch, synchronized, this, throw, throws, transient, true, try, typeof, var, void, volatile, while, with, yield

Les deux let et var peuvent être utilisés pour créer des variables, bien qu’il ne s’agisse pas de la même chose.
Var provient de la syntaxe JavaScript originale, tandis que let a été ajouté plus tard.

let ne permet pas de déclarer une autre variable du même nom, var le fait, ce qui peut poser des problèmes lors de l'exécution du programme.

Ajouter de la valeur à une variable avec = 

L'interprète reconnaît la valeur et l'affiche dans le terminal, mais le même mot entre guillemets sera interprété comme du texte.

Les variables en JavaScript ne sont pas typées. Cela signifie que la valeur ajoutée n’est pas contrôlée. Peut avoir commencé par un nombre et se transformer facilement en chaîne.
