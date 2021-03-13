//# LabTask


import java.util.*;



public class task1 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		
		/*******************************************************************
		 *  
		 * Task 1.................
	
		 */
	
		Scanner Input= new Scanner(System.in);
		/*System.out.println(" Enter the percentage of Student :");
		int num= Input.nextInt();
		
		
		if (num >= 90)
		{
			System.out.println("A Grade");
		}
		
		else if (num>=75)
		{
			System.out.println(" B Grade");
		}
		
		else if (num>=65)
		{
			System.out.println("C Grade");
		}
		
		
		else if (num>=50)
		{
			System.out.println("D Grade");
		}
		
		else
		{
			System.out.println("Fail");
		}
		*/
		/*****************************************/
	/*	System.out.println("Input the Grade of Student");
		String grade = Input.nextLine();
		
		
		
		switch(grade)
		{
		
		case "A" : System.out.println(" Your percentage is 90");
		break;
		case "B" : System.out.println(" Your Percentage is 75");
		break;
		case "C": System.out.println("Your Percentage is 65 ");
		break;
		case "D": System.out.println("Your Percentage is 50");
		break;
		default: System.out.println("You are Fail");

		
		
		
		
		}
		
		
		*/
		
		
		
			/*********************\\\\\\\
			 * 
			 * Task 2
			 * 
			 * 
			 */
		
		/*
		for (int i=0; i<100; i++)
		{
	
		//System.out.println("Enter the Number for which you check the divisibility :");
		//int i = Input.nextInt();
		
		if (i <=100 && i >=1)
		{
			if (i%3==0 && i%5==0)
			{
				System.out.println( i +" AlphaBeta ");
			}else if(i%5==0)
			{
				System.out.println( i + " Beta");
			}else if(i%3==0)
			{
				System.out.println(i + " Alpha");
			}else 
			{
				// Empty
			}
		}		
			
		}
		
		*/
		
		/***********
		 * 
		 * 
		 * Task 3
		 * 
		 * 
		 */
	/*	System.out.print("Enter the number :");
		int num2= Input.nextInt();
		
		int sum=0;
		System.out.println("The Inverse is :");
		if (num2>1)
		{
			for(int i=num2; i>=1; --i)
			{
				System.out.print(" "+ i);
				sum+=(i*i);
			}
			
			
		}else
		{
			System.out.println("Please Enter the number greater than 1");
		}
		System.out.println();
		
		System.out.println("The Sum is " + sum);
		
		*/
		
		
		
		/************
		 * 
		 * Task 4
		 * 
		 */
		
		int []array= {1,2,3,4,5,6,7,8,9};
		System.out.print("The Origional Array is [ ");
		for(int i=0; i<array.length; i++)
			
		{
			System.out.print(" " + array[i]);
			
			
		}
		
		System.out.print(" ] \n The Reverse array is " );
		System.out.print("[");
		
		for(int i=array.length-1; i>=0; --i)
		{
			System.out.print(" " + array[i]);
			
		}
		
			System.out.println(" ]");
		

	}

	}
