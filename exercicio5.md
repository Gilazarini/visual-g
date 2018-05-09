# visual-g
Var
// Seção de Declarações das variáveis
gasolina: real
gas: real
litros: real
total: real
Inicio
// Seção de Comandos, procedimento, funções, operadores, etc...
      gas <- 3,49
    escreval ("Quantos reais de gasolina você quer colocar em seu carro?")
    leia (gasolina)
      litros <- gasolina/gas
      escreval ("O preço ficou em", gasolina, " reais")
      escreval ("Você conseguiu colocar",litros," litros de gasolina")
