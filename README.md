package Com.Sample;
import java.util.Scanner;
public class DimondPattern {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
				// TODO Auto-generated method stub
				Scanner sc=new Scanner(System.in);

				System.out.println("enter the no.of rows :");

				int n=sc.nextInt();

				for(int i=0;i<=n;i++) {

				for(int j=0;j<n-i;j++) {

				System.out.print(" ");

				}

				for(int k=0;k<2*i-1;k++) {

				System.out.print("*");

				}

				System.out.println();

				}

				for(int i=1;i<n;i++) {

				for(int j=0;j<i;j++) {

				System.out.print(" ");

				}

				for(int k=0;k<2*n-2*i-1;k++) {

				System.out.print("*");

				}

				System.out.println();

				}

	}

}

OUTPUT : 
   *
  ***
 *****
*******
 *****
  ***
   *
