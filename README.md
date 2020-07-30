# Welcome to GitHub Desktop!

This is your README. READMEs are where you can communicate what your project is and how to use it.

Write your name on line 6, save it, and then head back to GitHub Desktop.
namespace QuickKartTestApp
{
	public class Customer
    {
        public int customerId = 1;
        public string customerName = "Alan";
        public string address;
        public long phoneNumber;

        public Customer()
        {
            Console.WriteLine("Hello world, ", customerName, "no. ", customerId);
        }
    }
	
    class Program
    {
        static void Main(string[] args)
        {
            Customer customer1 = new Customer();
        }
    }
}