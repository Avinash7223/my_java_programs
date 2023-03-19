import java.lang.*;
import java.util.Scanner;

public class Main
{
	public static void main(String[] args) 
	{
		Scanner sc = new Scanner(System.in);
		
		
		String name,reve;
		int i;
		char ch;
		
		name=sc.next();
		reve="";
		
		for(i=0;i<name.length();i++)
		{
		    ch=name.charAt(i);
		    reve=ch+reve;
		}
		
		System.out.println(""+reve);
		
	}
}
