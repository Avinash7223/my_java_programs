import java.lang.*;
import java.util.Scanner;

public class input_print {
  public static void main(String[] args) {

    Scanner sc = new Scanner(System.in);

    String name;

    int roll;

    float gp;

    name = sc.next();

    roll = sc.nextInt();

    gp = sc.nextFloat();

    System.out.println("" + name);

    System.out.println("" + roll);

    System.out.println("" + gp);
  }

}