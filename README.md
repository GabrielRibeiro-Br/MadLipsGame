# MadLipsGame
MadLibsGame é um jogo interativo de palavras onde o jogador insere termos aleatórios (como substantivos, verbos, adjetivos) para preencher lacunas em uma história pré-definida.

import java.util.Scanner;
public class MadLipsGame {
    public static void main(String[] args){

        //MAD LIBS GAME

        Scanner scanner = new Scanner(System.in);

        String adjective1;
        String noun1; //Person, place or thing
        String adjective2;
        String verb1;
        String adjective3;

        System.out.println("Enter a adjective (Description): ");
        adjective1 = scanner.nextLine();
        System.out.println("Enter a noun (Person, place or animal): ");
        noun1 = scanner.nextLine();
        System.out.println("Enter a adjective (Description): ");
        adjective2 = scanner.nextLine();
        System.out.println("Enter a verb ending with -ing(Action)");
        verb1 = scanner.nextLine();
        System.out.println("Enter a adjective (Description): ");
        adjective3 = scanner.nextLine();

        System.out.println("Today i went to "+ adjective1 + " zoo.");
        System.out.println("And i saw a "+ noun1 +"." );
        System.out.println(noun1 + " was " + adjective2 + " and " + verb1 +"!");
        System.out.println("I was "+ adjective3 +"!");

        scanner.close();

    }
}

