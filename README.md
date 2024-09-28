# samples
#Data Types, Variables, Methods
namespace practiceConsoleApp2
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("enter the value of x:");
            int x = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("enter the value of y:");
            int y = Convert.ToInt32(Console.ReadLine());
            x = x + y;
            y = x - y;
            x = x - y;
            Console.WriteLine("after swapping x:"+x);
            Console.WriteLine("after swapping:"+y);
            Console.ReadLine();
        }
    }
}
