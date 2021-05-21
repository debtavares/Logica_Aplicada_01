# Lógica aplicada - JavaScript :zap:

###### Semana 2 - {Reprograma}

<br>O aprendizado semanal no JS foi através do Visual Studio Code, declarando variáveis e utilizando o console.log() para emissão de informações no terminal do programa.

<br> **O que são variáveis?**<br>
Como o nome já diz, variáveis são valores que podem ser alterados. Na computação, é um espaço na memória que armazena dados que podem ser alterados quando necessário. Exemplo:

```Var Nome = Debora```

A variável Nome recebe o dado Debora.

**Características de uma variável:**<br>
- Não pode começar com número, conter espaço ou usar palavra reservada. <br>
- Pode começar com letra, $ ou _. <br>
- Pode usar acento, símbolo e número. 

Outra forma de declarar variável é através do **let**. Let e Var simbolizam variáveis, a diferença é que Var possui um escopo global. 
E o oposto de Variável é Constante (**Const**), um valor que não pode ser alterado ou reatribuído.

**Questões resolvidas**:

``` 
    1 - Solicite o preço de uma mercadoria e o percentual de desconto 20%. Exiba no console o valor a pagar.

    2 - Calcule o tempo de uma viagem de carro. Pergunte a distância a percorrer e a velocidade média esperada para a viagem.

    3 - Crie um algoritmo que leia o valor de um jantar, calcule e informe o valor da taxa do garçom (10%) e o valor total a ser pago.

    4 - Escreva um programa que pergunte a quantidade de km percorridos por um carro alugado pelo usuário, assim como a quantidade de dias pelos quais o carro foi alugado. Calcule o preço a pagar, sabendo que o carro custa 60,00 reais por dia e 0,15 centavos por km rodado.

    5 - Receba do usuários 3 números e calcule a média entre eles.

    6 - Elabore um algoritmo que receba um número (1-7) e devolva o dia da semana correspondente.

    7 - Elabore um algoritmo que receba dois números e determine qual é o maior entre eles, se os números forem iguais, mostre uma mensagem no console "Os números são iguais".

    8 - Crie um algoritmo que receba três notas de um aluno, calcule sua média e mostre as seguintes mensagens de acordo com cada situação:

        - Se a media for igual ou maior que 7 - Aprovado
        - Se a media for maior e igual a cinco e menor que 7 - Recuperação
        - Se a media for menor que 5 - Reprovado

    9 - Crie uma variavel que retorna a palavra (impar/par) de acordo com seu parâmetro.

    10 - Crie uma variavel que recebe o ano de nascimento da pessoa informando se ela é maior de idade ou menor.

```
<br> **Comentário das resoluções**:

**1ª -** Foram criadas três variáveis, uma para receber o preço da mercadoria (x), a segunda para calcular o desconto de 20% (x * 0,2) e a terceira para calcular o valor menos o desconto. No fim, mostrar o valor que irá pagar na tela.

<br>**2ª -** O tempo de viagem é calculado pela velocidade media dividido pela distância. Novamente, três variáveis são criadas para ser atribuída essas informações e o calculo aparecer na tela através do console.log().

<br>**3ª -** Três variáveis referentes ao valor do jantar, taxa (0,1 * x) e o total, que é a soma das duas primeiras variáveis.

<br>**4ª -** Duas variáveis referentes ao KM rodado e a quantidade de dias. A fórmula utilizada foi (km*0.15+(dias*60)). 

<br>**5ª -** Três variáveis de entrada de números, depois calculo da média (n1+n2+n3/3)

<br>**6ª -** Uma variável é criada para que se receba um numero de 1 a 7, referente aos dias da semana, e o escopo retorna o dia da semana correspondente, através de if, else if e else. Também poderia ser utilizado o switch.

<br>**7ª -** Duas variáveis são criadas para receber um número cada, retornando a resposta sendo maior, menor ou iguais. 

<br>**8ª -** A média é calculada conforme o quesito 5ª, mas a diferença está no uso da condicional, onde o if simboliza  *se* , else if, *se não se* , e else simboliza *se não* .
Nesse caso, o se a média for maior que 7, o console retorna "aprovado". Se entre 5 e 7, retorna recuperação, caso contrário (não seja nenhuma das duas opções, ou seja, menor que 5) o console exibe reprovado.

<br>**9ª -** Uma variável recebe um número e a fórmula indica **if** (se) o resto da divisão por 2 retornar 0, o número é par, **else** (caso contrário) é ímpar.

<br>**10ª -** Uma Variável referente ao ano que nasceu e outra com a diferença do ano atual e o ano de nascimento informado. Se o resultado for > 18, retorna maioridade. Caso contrário, menoridade. 

<br>*That's all folks!*

![certificado](https://techbreak.ig.com.br/wp-content/uploads/2017/08/Guia-do-Mochileiro-das-Gal%C3%A1xias.gif)
