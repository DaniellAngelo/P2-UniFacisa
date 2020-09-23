# Operadores em JAVA

## Aritméticos: +, -, *, /, %
```java
    int a =  1  +  1 ;    // o valor de a será 2 
    a = a -  1 ;          // o valor de a será 1 
    a = a *  10 ;         // o valor de a será 10 
    a = a /  2 ;          // o valor de a será 5 
    a = a /  2 ;          // o valor de a será 2 (apenas a parte inteira, desprezando a parte decimal)

    int resto =  10  %  3 ; // o resto será 1
```
## Unários: ++, -, !
```java
    int a = 10 ;
    // primeiro examinemos os pós-fixados
    int b = a ++ ;       // a é atribuído para b (10), e depois a é incrementado (11) 
    int c = a - ;        // a é atribuído para c (11), e depois a é dencrementado (10)

    // depois examinemos os pré-fixados 
    int d =  ++ a;          // a é incrementado (11), e depois a é atribuído para d (11) 
    int e =  - a;          // a é decrementado (10), e depois a é atribuído para d (10)

    // booleano 
    boolean f =  verdadeiro ;
    f =  ! f;                 // inverte o valor de f para false 
    f =  ! verdade ;          // mantem o valor de f em false 
    f =  ! falso ;            // altera o valor de f para true
```
## Relacionais de comparação e igualdade:

    <        maior que  
    >        menor que
    <=       menor igual
    >=       maior igual
    ==       igual
    !=       diferente

## Lógicos: &&, ||
```java
    booleano v1 =  verdadeiro ;
    booleano v2 =  falso ;

    boolean v3 = v1 && v2;    // v3 é false 
    v3 = v1 || v2;            // v3 é verdadeiro
```
## Ternário: ? : (tem o mesmo efeito de um comando condicional if-else)
```java
    int altura =  180 ;
    String classificacao = altura >  160  ?  " alto "  :  " baixo " ;

    // equivale ao seguinte comando if-else 
    String classificacao =  " " ;
    se (altura >  160 )
    classificacao =  " alto " ;
    else 
    classificacao =  " baixo " ;
    ```