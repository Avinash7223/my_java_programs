import java.lang.*;
import java.io.*;

class ArithmeticOp
{
	char a;
	char b;
	ArithmeticOp(){}
	ArithmeticOp( char x, char y){a=x; b=y;}

	void add() { int t=a+b; System.out.println(a + " + " + b + " = " + t );}
}	
public class Pro22
{
  public static void main(String[] args) throws IOException 
  {
	InputStreamReader isr = new InputStreamReader(System.in);
	BufferedReader br= new BufferedReader(isr);
	char n,m;
	System.out.print("\n Enter a char for a =  ");
	n = br.readLine().charAt(0);
	System.out.print("\n  Enter b char for b =  ");
	m =br.readLine().charAt(0);
	ArithmeticOp ob1 =new ArithmeticOp(n,m);
	ob1.add();
	
   }
}
	

