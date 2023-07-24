# Loops.java
com.java.basics

package com.java.basics;

public class Loops {

	public static void main(String[] args) {
		
		
		
		// 1 to 10
		System.out.println(1);
		System.out.println(2);
		System.out.println(3);
        
		
		//For loop
		
		for(int i=1; i<=10;i++) {//initialization; condition; updation
			System.out.println(i);
			
			
			
			//for(;;) {
				//System.out.println("Looping...");
				
			//}
			
			
			int j = 0;
			while (j < 100) {
				 
				if (j % 2 == 0) {
					System.out.print(j + " ");
				}
				j++;
			}
			
			do {
				System.out.println("Running do while");
				
			}while(4 ==5);
			
		}
		
	}

}
