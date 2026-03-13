#EX1

import java.util.Scanner;

public class EX1 {
    public static void main (String[] args){
        Scanner sc = new
Scanner(System.in);

        int[] vetor = new int[5];

        for (int i = 0; i < 5; i++){
            System.out.print("Digite um número:");
            vetor[i] = sc.nextInt();
        }

        System.out.println("Números digitados: ");
        for (int i = 0; i < 5; i++){
            System.out.println(vetor[i]);
        }
    }
}



#EX2

import java.util.Scanner;

public class EX2 {
    public static void main(String[] args){
        Scanner sc = new
Scanner(System.in);

            int[] num = new int[5];
            int soma = 0;

            for (int i = 0; i < 5; i++){
                System.out.print("Digite um número: ");
                num[i] = sc.nextInt();
                soma += num[i];
            }
           int maior = num[0];
            int menor = num[0];

            for( int i = 1; i < 5; i++){
                if(num[i] > maior) maior = num[i];
                if(num[i] < menor) menor = num[i];

            }
            double media = soma / 5.0;

            System.out.println("média: " + media);
            System.out.println("maior: "+ maior);
            System.out.println("menor; " + menor);
    }
}


#EX3

 public static void main(String[] args){
        Scanner sc = new
Scanner(System.in);
         
         System.out.print("digite uma frase: ");
         String frase = sc.nextLine().toLowerCase();
         
         int cont = 0;

         for(int i = 0; i < frase.length(); i++){
            char c = frase.charAt(i);
            
            if(Character.isLetter(c) && "aeiou".indexOf(C) == -1){
            System.out.println(c);
            cont++;

         }

         }
    }



#EX4


import java.util.Scanner;

public class EX4 {
    public static void main(String[] args){
        Scanner sc  = new
Scanner(System.in);

       double[]  notas = new double[4];
       double soma = 0;

       for(int i = 0; i < 4;i++){
        System.out.print("Digite a nota: ");
        notas[i] = sc.nextDouble();
        soma += notas[i];
       }
         double maior = notas[0];
         double menor = notas[0];

         for(int i = 1; i < 4;i++){
            if(notas[i] > maior) maior = notas[i];
            if(notas[i] < menor) menor = notas[i];
         }
    
         double media = soma / 4;
            System.out.println("média: " + media);
            System.out.println("maior nota: " + maior);
            System.out.println("menor nota: " + menor);

    }
}


#Ex5
 import java.util.Arrays;
import java.util.Scanner;

public class Ex5 {
    public static void main(String[] args){
        Scanner sc = new
Scanner(System.in);

        int [] A = new int[10];
        int[] B = new int[20];
        int[] C = new int[30];

        for(int i = 0; i < 10; i++){
            System.out.print("A[" + i + "]: ");
            A[i] = sc.nextInt();
        }
        for (int i = 0; i < 20; i++){
            System.out.print("B[" + i + "]: ");
            B[i] = sc.nextInt();
        }
        for (int i = 0; i < 10; i++){
            C[i] = A[i];
        }
          Arrays.sort(C);

        System.out.println("Vetor C ordenado: ");
        for (int i = 0; i < 30; i++) {
            System.out.println(C[i]);
        }
    }
}
    



