namespace divideWithoutReminder
{
    internal class Program
    {
        static void Main(string[] args)
        {
            int n = int.Parse(Console.ReadLine());
            int p1 = 0;
            int p2 = 0;
            int p3 = 0;
             
            for(int i =1; i <= n; i++)
            {
                int number= int.Parse(Console.ReadLine());
                if(number%2 == 0)
                {
                    p1 = p1 + 1;
                }
               
                if (number % 3 == 0)
                {
                    p2 = p2 + 1;
                }
                if (number % 4 == 0)
                {
                    p3 = p3 + 1;
                }
            }
            double percentage1 = (p1 * 100.0) / n;
            double percentage2 = (p2 * 100.0) / n;
            double percentage3 = (p3 * 100.0) / n;

            Console.WriteLine("{0:F2}%",percentage1);
            Console.WriteLine("{0:F2}%", percentage2);
            Console.WriteLine("{0:F2}%", percentage3);
        }

    }
}
