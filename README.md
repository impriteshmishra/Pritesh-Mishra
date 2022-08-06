# Pritesh-Mishra
Mathematical Calculators Programming using Basic concepts of Java language.
package com.company;
import java.util.Scanner;
public class Calculator {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the required operator (+,-,*,/):");
        char operator = sc.next().charAt(0);
        System.out.println("Enter first number: ");
        float a = sc.nextFloat();
        System.out.println("Enter second number:");
        float b = sc.nextFloat();
        if (operator == '+') {
            float sum = a + b;
            System.out.println(sum);
        }
             else if (operator == '-') {
                float minus = a-b;
                System.out.println(minus);
        } else if (operator == '*') {
            float multiplication = a*b;
            System.out.println(multiplication);
        } else if (operator == '/') {
                 float divide = a/b;
            System.out.println(divide);
        }
             else {
            System.out.println("Nothing..........");
        }
    }
}
