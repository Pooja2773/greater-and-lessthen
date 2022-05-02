# greater-and-lessthen
hey

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace greaterthan_and_lessthen
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Enter the first nummber");
            int a = int.Parse(Console.ReadLine());

            Console.WriteLine("Enter the second nummber");
            int b = int.Parse(Console.ReadLine());


            Console.WriteLine("Enter the third nummber");
            int c = int.Parse(Console.ReadLine());

            if (a > b && a > c)
            {
                Console.WriteLine("A is greater");
            }
            else if (b > c)
            {
                Console.WriteLine(" B is greater ");
            }


            else
            {
                Console.WriteLine(" C is greater ");
            }

            Console.ReadKey();    
        }
    }
}
