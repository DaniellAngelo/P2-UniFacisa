# Estruturas de Repetição

## While - Do while -  For 

## While
While: só executa o escopo do comando "while" se a condição for verdadeira.

```java
public static void main(String[] args) {

int i = 0;
        while(i <= 9) {
            i = i + 1;
            System.out.println( i );
        }
}

// outro exemplo de While

import java.util.Scanner;
public class ParesPositivos {
    public static void main (String [] args) {

        // Programa que recebe como entrada 15 números
        // e exiba a quantidade de números que são pares e positivos.

        Scanner entrada = new Scanner(System.in);
        int contParesPositivos = 0;

        int i = 1;
        while(i <= 25){
            System.out.println("Digite um número ");
            int num = entrada.nextInt();
            if (num % 2 == 0 && num > 0)
                contParesPositivos++;
            i++;
        }
        System.out.println("A quantidade de numeros positivos é "+contParesPositivos);
    }    
}
```
## Do while
Do While: executa o escopo do comando "do" independentemente da condição ser verdadeira.
```java
public static void main (String [] args) {
        int cont = 1;
        do {
            System.out.println ("Contagem é:" + cont);
            cont ++;
        } enquanto (cont < 11);
    }

    // outro exemplo de do While

import java.util.Scanner;
public class ParesPositivos {
    public static void main (String [] args) {

        Scanner entrada = new Scanner(System.in);
        int contParesPositivos = 0;

        int i = 1;
        do{
            System.out.println("Digite um número ");
            int num = entrada.nextInt();
            if (num % 2 == 0 && num > 0)
                contParesPositivos++;
            i++; 
        }
        System.out.println("A quantidade de numeros positivos é "+contParesPositivos);
    }
}
```
## For
A estrutura do for, é usada geralmente quando se sabe a quantidade de iterações.
```java
import java.util.Scanner;
public class ParesPositivos {
    public static void main (String [] args) {

        Scanner entrada = new Scanner(System.in);
        int contParesPositivos = 0;

        for (int i = 1; i <= 25; i++) {
            System.out.println("Digite um número ");
            int num = entrada.nextInt();
            if (num % 2 == 0 && num > 0)
                contParesPositivos++;
        }
        System.out.println("A quantidade de numeros positivos é "+contParesPositivos);
    }
}
```