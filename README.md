package com.company;

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.println("enter the first number");
        int number1 = scanner.nextInt();
        System.out.println("enter the 2nd number");
        int number2 = scanner.nextInt();
        int add = (number1 + number2);
        System.out.println( "the sum of the number is, " + add );
    }
}
