# Desafios Para Resolver

## Criar Matriz de Xadrez ou Dama 8x8
~~~
   a  b  c  d  e  f  g  h
 1
 2
 3 
 4 
 5
 6
 7
 8
~~~
## Criar Mapa Com Plano Cartesiano
~~~
          +3
          +2
          +1
 -3 -2 -1  0  +1 +2 +3
          -1
          -2
          -3
~~~
e com o plano carteriano criar as Seguintes atividades
- campo minado
- entregas no mapa
- mirar e acertar o pato

## Menu Com Procedimento
  
~~~ alg
Algoritmo "menu de opções"

var
  sair : logico
  escolhido : inteiro

  Procedimento TelaInicial
    Inicio
      Escreval("Caso [1], Caso [2], Caso [3], Caso [4], Sair [0]")
  FimProcedimento

  Procedimento ModulosPrograma (escolhido : inteiro)
    Inicio
      LimpaTela
      Escolha (escolhido)
        Caso 1
          Escreval("> 1")
        Caso 2
          Escreval("> 2")
        Caso 3
          Escreval("> 3")
        Caso 4
          Escreval("> 4")
        OutroCaso
          Escreval("> Nao Sei")
      FimEscolha
  FimProcedimento

Inicio
  Repita
    TelaInicial
    Leia(escolhido)

    Se (escolhido = 0) Entao
      sair <- verdadeiro
      Escreval("Finalizando o Programa")
    Senao
      ModulosPrograma(escolhido)
    FimSe
  Ate (sair = verdadeiro)

FimAlgoritmo
~~~
