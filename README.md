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
