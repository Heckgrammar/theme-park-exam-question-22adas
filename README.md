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
        
        Console.WriteLine("Total charge for"+people+ "people: £"+total);<img width="324" alt="Screenshot 2025-04-21 at 15 50 05" src="https://github.com/user-attachments/assets/abd8148d-42f0-47e0-bd85-87d091f79528" />

	}
}
