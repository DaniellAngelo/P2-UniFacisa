Estruturas Condicionais

if - else if - else

Usa-se "if, else if e elif" quando precisar fazer comparações. Chaves "{", "}" são obrigatórias quando há multiplas linhas no comando após a condição, quando apenas uma linha é opcional.

    Scanner scanner =  novo  Scanner ( Sistema . In);
    int idade = scanner . nextInt ();

    if (idade < 30)
        System.out.println ("Jovem");
    else if (idade < 60)
        System.out.println ("Adulto");
    else (idade < 120)
        System.out.println ("Idoso");


Switch - case

Switch case serve apenas para comparar (==) valores primitivos inteiros e String, não podendo de usado com float ou double, >= , <= e comparações complexas usando operadores lógicos(&&, || ). a palvra "default" funciona como eu tipo de else.

    publi class DataTexto{

        //Formato data padrão: 09/07/2020
        //Formato data texto: 5 de julho de 2020
        
        public static void main(String[] args){
            short dia = 9, mes = 7, ano = 2020;
            String mesTexto = converteMesNumParaTexto(mes);
            System.out.println(dia+" de "+mesTexto+" de "+ano);
        }    

        public static String converteMesNumParaTexto(short mes){
            switch(mes){
                case 1: return "Janeiro";
                case 2: return "Fevereiro";
                case 3: return "Março";
                case 4: return "Abril";
                case 5: return "Maio";
                case 6: return "Junho";
                case 7: return "Julho";
                case 8: return "Agosto";
                case 9: return "Setembro";
                case 10: return "Outubro";
                case 11: return "Novembro";
                case 12: return "Dezembro";
                default: return "mês inexistente"
            }
        }
    }