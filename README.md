using System;

class Program
{
    static void Main()
    {
        Console.WriteLine("Enter your name:");
        string name = Console.ReadLine();

        string greeting = GenerateGreeting(name);
        Console.WriteLine(greeting);

        Console.ReadLine(); // Keep the console window open
    }

    static string GenerateGreeting(string name)
    {
        return $"Hello, {name}! Welcome to the .NET world.";
    }
}
