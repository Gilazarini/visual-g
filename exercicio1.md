# visual-g 
Var
// Seção de Declarações das variáveis 
L1:inteiro
L2:inteiro
total:inteiro
Inicio
// Seção de Comandos, procedimento, funções, operadores, etc... 
     escreval ("escreva o primeiro lado do retangulo")
     leia (L1)
     escreval ("escreva o segundo lado do retangulo")
     leia (L2)
     
      enquanto L1 = L2 faca
       escreval ("os dois lados não podem ser iguais pois é um quadrado,digite novamente")
           escreval ("escreva o primeiro lado do retangulo")
            leia (L1)
           escreval ("escreva o segundo lado do retangulo")
            leia (L2)
       total <- L1*L2
       escreval ("o resultado é",total)
       fimenquanto
