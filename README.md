# trabalhos-
class Program
{
    static void Main()
    {
        int[] numeros = new int[7];

        for (int i = 0; i < 7; i++)
        {
            Console.Write($"Digite o {i + 1}º número inteiro: ");
            numeros[i] = int.Parse(Console.ReadLine());
        }

        Console.WriteLine("\nNúmeros na ordem inversa:");
        for (int i = 6; i >= 0; i--)
        {
            Console.WriteLine(numeros[i]);
        }
    }
}
