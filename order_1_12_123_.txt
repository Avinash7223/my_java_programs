import java.lang.*;
import java.util.Scanner;

public class Main
{
	public static void main(String[] args) 
	{
		Scanner sc = new Scanner(System.in);
		
		int i,j,num;
		
		num=sc.nextInt();
		
		for(i=1;i<=num;i++)
		{
		    for(j=1;j<=i;j++)
		    {
		        System.out.print(j);
		    }
		    
		    System.out.println();
		}
		
	}
}