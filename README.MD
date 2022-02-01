using System;

namespace power
{
    class Program
    {
        public void power12()
        {
            Console.WriteLine("enter the base number");
            int x = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("enter a number");
            int n = Convert.ToInt32(Console.ReadLine());
            int i = 0;
             int power = 1;
            if (x == 0&&n==0)
            {
                Console.WriteLine("not possible");
            }
            
            
                for(i=1;i<=n;i++)
                {
                  power = power * x;
                }
                Console.WriteLine(power);
            }
        static void Main(string[] args)
        {
            Program pr = new Program();
            pr.power12();
        }
    }
}
