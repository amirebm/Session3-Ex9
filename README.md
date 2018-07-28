# Session3-Ex9

// ب ن ک اعدادی رو از ورودی گرفته تا هنگامی که کاربر عدد منفی یک را بزند ، سپس کوجکترین عدد وارد شده را چاپ کند


package com.personal.ex9;

import java.util.Scanner;
import java.util.Vector;

public class ex9 {

	public static void main(String[] args) {

		Scanner sc= new Scanner(System.in);
		System.out.println("Enter a Number");
		int temp=0,min;
		min= sc.nextInt();
		while(temp!=-1) {
		 temp=sc.nextInt();
		 
		if (temp<min && temp!= -1)
		 min=temp;
		 
		} 
		System.out.println("the min number is " + min);

		
	}

}
