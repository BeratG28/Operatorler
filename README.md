# Operatorler

https://app.patika.dev/courses/csharp-101/5-operatorler


Patika.dev C# Eğitim kapsamında ödev 


using System;

namespace MyApp // Note: actual namespace depends on the project name.
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("**Mantıksal Operatorler**");
        //Atama ve işlemli atama
        int x = 3;
        int y = 3;
        y= y+2;
        
        Console.WriteLine(y);
        y += 2;
        Console.WriteLine(y);
        y /= 1;
        Console.WriteLine(y);
        x +=2;
        Console.WriteLine(y);

        //Mantıksal Operatorler        
        
        //, ||, &&, !
        bool isSuccess = true;
        bool isCompleted = false;
         if(isSuccess && isCompleted)
             Console.WriteLine("Perfect!");
         if(isSucces || isCompleted);
              Console.WriteLine("Great!");

         Console.WriteLine(**İlişkisel Operatörler**);
         //İliskisel Operatorler
         int a = 3;
         int b = 4;
         bool sonuc = a<b;

         Console.WriteLine(Sonuc);
         sonuc = a<b;
         Console.WriteLine(Sonuc);
         sonuc=a!=b;
         Console.WriteLine(Sonuc);

        }
    }
}
