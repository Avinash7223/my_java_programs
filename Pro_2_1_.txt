import java.lang.*;
import java.io.*;

class ArithmeticOp
{
	int a;
	int b;
	ArithmeticOp(){}
	ArithmeticOp( int x, int y){a=x; b=y;}

	void add() { int t=a+b; System.out.println(a + " + " + b + " = " + t );}
}	
public class Arithmetic
{
  public static void main(String[] args) throws IOException 
  {
	InputStreamReader isr = new InputStreamReader(System.in);
	BufferedReader br= new BufferedReader(isr);
	int n,m;
	System.out.print("\n Enter a value for a =  ");
	n = Integer.parseInt(br.readLine());
	System.out.print("\n  Enter b value for b =  ");
	m = Integer.parseInt(br.readLine());
	ArithmeticOp ob1 =new ArithmeticOp(n,m);
	ob1.add();
   }
}
	

