# Semáforo com radar de velocidade

## Projeto feito no Autodesk Tinkercad

1. ### OBJETIVO

   ##### O projeto em questão tem como objetivo operar tanto um radar quanto um semáforo, utilizando o mesmo Arduíno UNO. Para isso, a quantidade de  "delay()" na sintaxe do código foi reduzida ao seu máximo, de forma que ambas as funções pudessem ser executadas simultaneamente. 

2. ### ONDE ENCONTRAR O PROJETO

   ##### O projeto está no Tinkercad, em meu nome, e pode ser acessado através do link a seguir: [Semáforo com radar de velocidade](https://www.tinkercad.com/things/5nnGxC2Tb7D).
   
3. ### SOBRE A PROGRAMAÇÃO

   ##### A programação mais atual está disponível no GitHub e críticas são sempre muito bem vindas! A única coisa que peço, com muito zelo, é que qualquer alteração seja comentada, afinal, nem sempre é fácil de entender o que a programação nos diz apenas através da leitura do código. O próprio Tinkercad proporciona uma ferramenta de simulação, então qualquer alteração eu vou tomar a liberdade de simular e, caso apresente mal funcionamento, excluirei.

4. ### ALGUNS PROBLEMAS CONHECIDOS

   ##### Como já foi dito, o uso de "delay()" foi minimizado pois atrapalha a execução de funções concomitantes, ou seja, o "delay()" que está presente na função do radar atrapalha a execução do semáforo. Assim, a prioridade atual é trocar o "delay()" do radar por algo que mantenha a função viável para o projeto.