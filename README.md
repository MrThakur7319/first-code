# first-code
i learn to use scanner in java

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);   //i create scanner
        System.out.println("enter the number:"); //i ask the user enter the number
        int num = sc.nextInt();
        System.out.println("enter the letter:");
        String name = sc.next();  //i ask the user enter the letter
        System.out.println("number: " + num + " letter: " + name);
        sc.close();
    }
}
