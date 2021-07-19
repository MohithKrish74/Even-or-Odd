package com.company;

import java.util.*;

public class Main
{
    public static void main(String[] args)
    {
        Scanner in =new Scanner(System.in);
        System.out.print("Enter the number");
        int number=in.nextInt();
        if(number%2==0)
            System.out.println("Even Number");
        else
            System.out.println("Odd Number");

    }
}
