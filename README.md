# Learn_c-.net_in_one_shot
Learn c# basics
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;

namespace ConsoleApplication1       // namespace is act as a container which is uset to store multiple classes....
{
    class Program
    {
        static void great(string name)
    {
       
        Console.WriteLine("gud nght " + name);

    }
        static void Main(string[] args)
        {
            //this is important do not remove it
            
            /*this is multeline comment 
             * which is used to spann multiple lines*/
            
            //Console.WriteLine("my name is aman raghava");
            // Console.Write("hello world");
            //Console.WriteLine("i love c# amd the number is "+aman);
            
            
            /*data type in c#
             * integer int aman=1;size= 4 byte
             * floting point number float a=10.5;size= 4 byte
             * character char aman='a';size= 2 byte
             * string string s="aman";size= 2byte per character
             * boolean bool isgreat=true;size =1 bits*/
         
            
            //string s = Console.ReadLine();
            //Console.ReadLine(s);

            //Console.ReadLine();

            //data type examples
          //  int a=10;
            //double b = 34.5D;
            //float c = 34.5F;
            //bool isgreat = true;
            //char d = 'q';
            //string e = "this is a string";
           
            //Console.WriteLine(a);
            //Console.WriteLine(b);
            //Console.WriteLine(c);
            //Console.WriteLine(isgreat);
            //Console.WriteLine(d);
            //Console.WriteLine(e);

           // Console.ReadLine();
            //type casting 
            //there are two type of type casting 
            //1. implicit casting
            //2. explicit casting
            // char to int to long to float to double
           // int x = 3;
            //double y = x;
            //Console.WriteLine(x);
            //Console.WriteLine(y);
            //Console.ReadLine();
            //Console.Writeline("enter your name");
            //string name = Console.Readline();
            //Console.Writeline("hello aman" + name);
            //Console.Writeline("how many candies do you went");
            //string can = Console.ReadLine();
            //
            //Console.Writeline("you will get 4 candies more" + (Convert.ToInt32(can) + 4));
            /*types of operators in c#
             * 1.arithmetic operator
             * 2.assignment operator
             * 3.logical operator
             * 4.comparision operator
             */
            //int a = 3;
            //int b = 4;
            //Console.WriteLine("sum of a+b is" + (a + b));
            //Console.Readline();
            /* int a = 4;
            int b = 3;
            case=(a + b);

            Console.WriteLine(case);*/
            //logical operator
          /*  Console.WriteLine(true && true);
            Console.WriteLine(false && true);
            Console.WriteLine(false && false);
            
            Console.WriteLine(true || true);
            Console.WriteLine(false || true);
            Console.WriteLine(false || false);
            Console.WriteLine(!true);
            Console.WriteLine(!false);*/
            //comprasion operator

          /*  Console.WriteLine(4>5);
            Console.WriteLine(6>5);
            int a = Math.Max(234, 55);
            Console.WriteLine(a);
            int b = Math.Min(234, 55);
            Console.WriteLine(b);
            double c = Math.Sqrt(25);
            Console.WriteLine(c);
            string s = "hii aman";
            Console.WriteLine(s.ToUpper());
            Console.WriteLine(s.ToLower());
            Console.WriteLine(s.Length);
            Console.WriteLine(s + " fuck");
            Console.WriteLine(string.Concat(s, " fuck"));
            int x= Math.Max(23,3);
            Console.WriteLine(x);
            string hello = "hii aman raghava";
                Console.WriteLine(hello.IndexOf("raghava"));
                Console.WriteLine(hello.Substring(2));
            
            Console.WriteLine("enter your age");
            string agestr = Console.ReadLine();
            int age = Convert.ToInt32(agestr);
            if (age > 18)
            {
                Console.WriteLine("you are eleigible for vote");
            }
            else
            {
                Console.WriteLine("you are not eligible for vote");
            }*/
           /* int age = 19;
            switch (age)
            {
                case 18:
                    Console.WriteLine("you have to wait for one year");
                    break;
                case 20:
                    Console.WriteLine("you can enjoy");
                    break;
                default:
                    Console.WriteLine("you can fuck");
                    break;
            }
            string s = "hii aman this is herry \n all about love";
            Console.WriteLine(s);
            string n = "hiii fuck\" all ";
            Console.WriteLine(n);
            string v = "hiii fuck \t all ";
            Console.WriteLine(v)
            //loops in c#
            int i=0;
            while (i < 5)
            {
                Console.WriteLine(i+1);
                i++;
            }
            int i = 0;
            do{
                Console.WriteLine(i + 1);
                i++;
            } while(i < 10);
           
            for (int i = 0; i < 10000000; i++)
            {
                Console.WriteLine(i + 1);
                break;
            }
            //break and continue statement
            //break - skip this loop forever
            //continue - skip this loop for one iteration
            //function in c#
           */
          great("aman");
          Console.ReadLine();

        }
    }
}
