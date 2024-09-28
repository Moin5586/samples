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


//Create a method to calculate the area of a rectangle.
static void Main(string[] args)
 {
     Console.WriteLine("enter the value of lengrh:");
     int length = Convert.ToInt32(Console.ReadLine());
     Console.WriteLine("enter the value of width:");
     int width = Convert.ToInt32(Console.ReadLine());
     int area = length * width;
     Console.WriteLine("area of rectangle is "+area);
     Console.ReadLine();
}


//storing nsmes
 static void Main(string[] args)
 {
     string[] studentNames = { "moin","mahesh","naresh","somesh","suresh","madesh"};
     Console.WriteLine(studentNames);
 }




