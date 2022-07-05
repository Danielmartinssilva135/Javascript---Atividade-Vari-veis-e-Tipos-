# Javascript---Atividade-Variáveis-e-Tipos-
Javascript - Atividade "Variáveis ​​e Tipos" do Bootcamp Santander -  Digital Innovation One.

Atividade 1 - Verifique, de duas maneiras diferentes entre si, se uma String é um palíndromo.

Palíndromo: frase ou palavra que se pode ler, indiferentemente, da esquerda para a direita ou vice-versa (ex.: raiar, ama, ovo, radar)

Primeiro verifiquei se a string existe, se ela era diferente de "true".  Utilizei  if(!string) return;
Dessa verifico se a variável é null, Empty ou Undefined.

//Solução 1
function verificaPalindromo(string){
    if(!string) return;

    string.split("").reverse().join("") === string;
}


Atividade 2 - Troque todos os elementos pares e diferentes de zero de um array pelo número 0. Se o array for vazio, rendimento -1.

Exemplo: Entrada -> [1, 3, 4, 6, 80, 33, 23, 90]

Saída -> [1, 3, 0, 0, 0, 33, 23, 0]

Entrada -> []

Saída -> -1
