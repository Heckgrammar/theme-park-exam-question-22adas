using System;
					
public class Program
{
	public static void Main()
	{
        double price = 15.00;
        double discount = 5.00;
        int minSizeForDiscount = 6;
        
        Console.Write("Enter the number of people in the group: ");
        int people = Convert.ToInt32(Console.ReadLine());
        
        double total = people * price;
        
        if (people >= minSizeForDiscount)
        {
            total = total - discount;
            Console.WriteLine("Group discount of £"+ discount +" applied!");
        }
        
        Console.WriteLine("Total charge for"+people+ "people: £"+total);
	}
}
<img width="324" alt="Screenshot 2025-04-21 at 15 52 54" src="https://github.com/user-attachments/assets/1dc7ee11-ccf5-4377-9695-429abb096a85" />
<img width="324" alt="Screenshot 2025-04-21 at 15 53 13" src="https://github.com/user-attachments/assets/ae2ab25a-1a33-4cc9-a69d-b255273b7e45" />
<img width="324" alt="Screenshot 2025-04-21 at 15 53 31" src="https://github.com/user-attachments/assets/2dfc90fa-20f7-4ebe-8938-296e6ddd5719" />


