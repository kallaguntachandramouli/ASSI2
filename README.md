1question
package greatest;

public class Add {
	public static void main(String[] args) {
		int a = 10;
		int b = 23;
		int c = 5;
		if (a > b && a > c) {
			System.out.println(a + " is the greatest number");
		} else if (b > a && b > c) {
			System.out.println(b + " is the greatest number");
		} else {
			System.out.println(c + " is the greatest number");	
		}
	}
} 

2quetion
package calcultor;

import java.util.Scanner;

public class Calcultor {
	public static void main(String[] args) {
		Scanner scanner = new Scanner(System.in);
		System.out.println("1. Addiion");
		System.out.println("2. Subtraction");
		System.out.println("3. Muliplcation");
		System.out.println("4. Division");
		
		System.out.println("Enter your choice: ");
		int choice = scanner .nextInt();
		System.out.println("Enter first  number: ");
		double num1 = scanner.nextDouble();
		System.out.println(" Enter second number: ");
		double num2 = scanner.nextDouble();
		switch (choice) {
		case 1:
			System.out.println("Reminder: " + (num1 + num2));
			break;
		case 2:
			System.out.println("Reminder: " + (num1 - num2));
		case 3:
			System.out.println("Reminder: " + (num1 * num2));
			break;
		case 4:
			if (num2 != 0)
				System.out.println("Reminder: " + (num1 / num2 ));
			else 
				System.out.println("Error: Division by zero!");
			break;
			default:
				System.out.println("Invalid choice!");
		}	
	}
}

3 question
package multiplicaion;

public class Multiplication {
	public static void main(String[] args) {
		int number = 7;
		int i = 1;
		System.out.println("Multipliction  Table of " + number);
		while (i <= 10) {
		System.out.println(number + " x " + i + " =  " + (number * i));
		i++;	
		}	
		}
}
4question
package oddnumber;

public class Oddnumber {
	public static void main(String[] args) {
		for (int i = 1; i <= 10; i++) {
			if (i % 2 == 0) {
				continue;
			}
			System.out.println(i);
		}
	}

}

