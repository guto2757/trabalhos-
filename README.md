# trabalhos-
using System;

class Program
{
    static void Main()
    {
        Console.Write("Digite sua idade: ");
        int idade = int.Parse(Console.ReadLine());

        if (idade < 12)
        {
            Console.WriteLine("Você é Criança.");
        }
        else if (idade >= 12 && idade <= 17)
        {
            Console.WriteLine("Você é Adolescente.");
        }
        else
        {
            Console.WriteLine("Você é Adulto.");
        }
    }
}
