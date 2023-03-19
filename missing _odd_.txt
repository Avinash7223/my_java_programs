import java.lang.*;
import java.util.Scanner;

public class Main
{
	public static void main(String[] args) 
	{
		Scanner sc = new Scanner(System.in);
		
		
		int i,j,num,odd;
		
		
		num=sc.nextInt();
		
		for(i=1;i<=num;i++)
		{
		    j=(2*i-1);
		    
		        if(j==7)
		        {
		            System.out.print("");
		            num++;
		        }
		        else if(j==17)
		        {
		            System.out.print("");
		            num++;
		        }
		        else if(j==23)
		        {
		            System.out.print("");
		            num++;
		        }
		        else
		        {
		            System.out.print(j);
		            
		        }
		}
		    
	}
}
/*


import java.lang.*;
import java.util.Scanner;

public class Main
{
	public static void main(String[] args) 
	{
		Scanner sc = new Scanner(System.in);
		for(int i=1;i<=26;i+=2)
		{ if( (i==7)||(i==17)||(i==23) ) continue;
		  else System.out.print(i+" ");
		}
	}
}
*/
