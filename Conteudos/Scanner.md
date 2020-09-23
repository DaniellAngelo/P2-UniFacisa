# Scanner

Scanner é uma classe do java que fica  no pacote java.util.
```java
    import java.util.Scanner;
```java
Objeto criado da classe scanner e atribuido à variável entrada (objeto contem funções que podem ser executadas). 
```java
    public static void main(String [] args) {

        Scanner entrada = new Scanner(System.in);
    }
```java
nextDouble() é uma função da classe Scanner, que pode ser executado a partir de objetos criados na classe Scanner. Ex: entrada.
```java
    double altura = entrada.nextDouble();
    double comprimento = entrada.nextDouble()
```java
    entrada.nextDouble()    para bouble
    entrada.nextInt()       para inteiro
    entrada.next()          para recebe String

Para receber o double com " . " (separador entre casa decimal e ponto flutuante).
```java
    import java.util.locale;

    entrada.useLocale(Locale.US);
```java