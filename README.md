// Напишите программу, которая на вход принимает число и выдаёт,является ли число чётным(Делится без остатка)
Console.WriteLine("Введите число ");
int x = int.Parse(Console.ReadLine()!);
if (x % 2 == 0)
{
    Console.WriteLine($"Да делится на 2");
}
else
{
    Console.WriteLine($"Нет не делится на 2");
}
