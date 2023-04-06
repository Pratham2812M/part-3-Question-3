static void CalculateTuitionFees(int numberofcourses, double costpercourse = 449.99)
        {
            double fees = numberofcourses * costpercourse;
            Console.WriteLine($"Your estimated tuition fee is ${fees}.");
        }
        static void Main(string[] args)
        {
            CalculateTuitionFees(5);
            Console.WriteLine();
            CalculateTuitionFees(6);
            Console.WriteLine();
