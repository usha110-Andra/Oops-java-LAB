package Com.Sample;

import java.util.Scanner;
import java.lang.*;

public class ElectricityBill {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner eb=new Scanner(System.in);
		System.out.println("Enter old reading : ");
		int oldReading=eb.nextInt();
		System.out.println("Enter current reading: ");
		int currentReading=eb.nextInt();
		int units=oldReading+currentReading;
		if(units<=50) {
			System.out.println("Total charge is to pay : "+units*1);
		}
		else if(50<units && units>=100) {
			System.out.println("Total charge is to pay : "+units*2);
		}
		else if(100<units && units<=200) {
			System.out.println("Total charge is to pay : "+units*3);
		}
		else if(200<units && units<=400) {
			System.out.println("Total charge is to pay : "+units*4);
		}
		if(units>400) {
			System.out.println("Total charge is to pay : "+units*5);
		}

	}
}


OUTPUT : 
Enter old reading : 
56
Enter current reading: 
49
Total charge is to pay : 210
