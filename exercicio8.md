# visual-g
Var
// Seção de Declarações das variáveis 
N1: real
N2: real
N3: real
disciplina: caracter
media: real
Inicio
// Seção de Comandos, procedimento, funções, operadores, etc... 
escreval("Qual disciplina você quer saber a média?")
leia(disciplina)

    escreval("digite sua primeira nota")
    leia(N1)
    escreval("digite sua segunda nota")
    leia(N2)
    escreval("digite sua terceira nota")
    leia(N3)
    
  media <- (N1+N2+N3)/3
    escreval ("A sua média na disciplina de ",disciplina," é de ",media," pontos")
