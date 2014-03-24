Hungry-Switch
=============
//   By  REINA  OLARTE
import java.util.Scanner;
public class HungryScwitch
{
public static void main(String[] args)
{
Scanner input = new Scanner(System.in);

String thirsty;

String Breakfast;

		//Print out commands
			System.out.println("Are you Hungry ?");

			System.out.println("Get in line");

			System.out.println("Buy Lunch\n");

//Ask if they are thirsty

			System.out.print("If you are thirsty press Y for yes N for no: ");

thirsty = input.nextLine().toUpperCase();

//Start of the Switch
			switch (thirsty)
			{
			case "Y":

				System.out.print("Have you had Breakfast press Y for yes N for no: ");
				
				Breakfast = input.nextLine().toUpperCase();
				
				switch(Breakfast)
				{
			case "Y":
					
				System.out.println("\nBuy a Diet Coke");
				
				break;
				
			case "N":
				
				System.out.println("\nBuy a coke");
				
				break;
				}
				break;
				
			case "N":
				
				System.out.println("\nBuy a water");
				
				break;
}
			System.out.println("Eat your Lunch");
			
			System.out.println("Return Tray");
			
			System.out.println("Your are full you may leave");
			
}			// End Method main

}			// End Class
