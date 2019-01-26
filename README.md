/*# DISCRIMINANT
This is a great code for solving square equations using a discriminant.
Here is the whole code
*/


using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;

namespace ConsoleApplication7
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("We have the formula ax2 + bx + c = 0, you need to lead a, b, c and for a couple of seconds!");
            Console.Write("a = ");
            int a = Convert.ToInt32(Console.ReadLine());

            Console.Write("b = ");
            int b = Convert.ToInt32(Console.ReadLine());

            Console.Write("c = ");
            int c = Convert.ToInt32(Console.ReadLine());

            int bkvadrat = b * b;
            int disci1 = bkvadrat;
            int discki2 = a * c;
            int discki3 = 4 * discki2;
            int last = bkvadrat - discki3;
            Console.WriteLine(last);


            Console.Write("exit = ");
            string str = Console.ReadLine();
            if (str == "no")
            {
                Console.WriteLine("We have the formula ax2 + bx + c = 0, you need to lead a, b, c and for a couple of seconds!");
                Console.Write("a1 = ");
                int a1 = Convert.ToInt32(Console.ReadLine());

                Console.Write("b1 = ");
                int b1 = Convert.ToInt32(Console.ReadLine());

                Console.Write("c1 = ");
                int c1 = Convert.ToInt32(Console.ReadLine());

                int bkvadrat1 = b * b;
                int disci11 = bkvadrat1;
                int discki21 = a * c;
                int discki31 = 4 * discki21;
                int last1 = bkvadrat1 - discki31;
                Console.WriteLine(last);


                Console.Write("exit = ");
                string str1 = Console.ReadLine();
                if (str1 == "no")
                {
                }
            }
        }
    }
} 
