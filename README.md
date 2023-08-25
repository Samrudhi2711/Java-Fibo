# Java-Fibo
 Upload the Local Repo on Local repo
 import java.lang.*;
import java.util.Scanner;
class fibonacci
{
	public static void main(String args[])
	{
		Scanner sc=new Scanner(System.in);
		
		System.out.println("Program to print fibonacci Series");
		System.out.println("Enter no. of term=");
		int n=sc.nextInt();
		int a=0,b=1,c;
		System.out.print(a+","+b);
		for(int i=0;i<n-2;i++)
		{
			c=a+b;
			System.out.print(c+",");
			a=b;
			b=c;
		}
	}
}
