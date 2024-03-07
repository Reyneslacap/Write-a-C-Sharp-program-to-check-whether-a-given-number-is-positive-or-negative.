using System;

class Program
{
    static void Main()
       
    {
       Console.WriteLine("Sir nag youtube po ako");
        Console.Write("Enter a number: ");
        int number = Convert.ToInt32(Console.ReadLine());

        if (number > 0)
            Console.WriteLine("{0} is a positive number.", number);
        else
            Console.WriteLine("{0} is a negative number.", number);
    }
    
}
