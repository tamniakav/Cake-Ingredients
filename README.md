# Cake-Ingredients
Just another repository
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Cake_Ingredients
{
    class Program
    {
        static void Main(string[] args)
        {
            string ingredient = Console.ReadLine();
            int counter = 0;

            while (true)
            {
                if (ingredient == "Bake!")
                {
                    break;
                }

                Console.WriteLine($"Adding ingredient {ingredient}.");
                counter++;

                ingredient = Console.ReadLine();
            }

            Console.WriteLine($"Preparing cake with {counter} ingredients.");
        }
    }
}
