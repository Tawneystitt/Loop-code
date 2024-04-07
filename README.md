<h1>Loop code</h1>

<h2>Description</h2>
This program demonstrates the use of nested loops in console application.


<h2>Used to create:</h2>

- <b>Visual Studios</b> 


<img src="https://i.imgur.com/d4nKtTO.png" height="80%" width="80%" alt="]"/>

<br/>

Code:
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Lab_6
{
    class Program
    {


        static void Main(string[] args)
        {


            Console.WriteLine("Pattern A"); //displays to user Pattern A

            const int Stars = 10; //constant integer is stars and is equal to 10 and this cant cha
            int t; // interger variable t established
            int e; // integer variable e established
            int w; // interger varaible w established

            for (t = 1;  Stars >= t;  t++) // variable t is equal to 1, t is less than or equal to stars, ++ means code is executing and will read it and add after it's been read
            {
                for (e = 1; t >= e; e++) // variable e is equal to 1, e is less than or equal to t, will add to design
                {
                    Console.Write("*"); //displays design
                }
                Console.WriteLine(); // space
            }
            Console.WriteLine("Pattern B"); //displays to user Pattern B
            for (t = Stars;  1 <= t; t--) // t is equal to stars. t is greater than or equal to 1, will decrement value 
            {
                for (e = 1; t >= e; e++)
                {
                    Console.Write("*"); //displays * on design
                }
                Console.WriteLine(); // adds blank space on design
            }

            Console.WriteLine("Pattern C"); //displays Pattern C to user
            for (t = 1; Stars >= t;  t++)
            {
                for (w = t; 1 < w; w--)
                {
                    Console.Write(" ");
                }
                for (e = Stars; t < e ; e--)
                {
                    Console.Write("*");
                }
                Console.WriteLine();
            }

            Console.WriteLine("Pattern D"); //displays Pattern D to user
            for (t = 1;  Stars >= t; t++)
            {
                for (w = Stars - 1; w >= t; w--)
                {
                    Console.Write(" ");
                }
                for (e = 1; t >=e; e++)
                {
                    Console.Write("*");
                }
                Console.WriteLine();
            }
            Console.WriteLine("Press any key to end Code"); //displays to the user to press any key to end code

            Console.ReadKey(); // prevents the code from closing until pressing a key
        }
    }
}

 <br/>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

