package Com.Sample;
import java.util.Scanner;
public class Palindrome {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

				Scanner sc=new Scanner(System.in);

				System.out.println("enter the no.of rows :");

				int n=sc.nextInt();

				for(int i=1;i<=n;i++) {

					int j=i;

					for(j=i;j>0;j--) {

						System.out.print(j);

					}

					for(j=2;j<=i;j++) {

						System.out.print(j);

					}

					System.out.println();

				}
	}

}

OUTPUT  :
enter the no.of rows :
4
1
212
32123
4321234

