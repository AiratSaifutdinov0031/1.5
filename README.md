Даны две переменные, значения которых необходимо обменять. Выведите значения переменных до и после обмена.
Примеры:У вас есть две переменные: имя и фамилия. Они инициализированы, но значения перепутаны. Нужно исправить это с помощью кода.Представьте, что у вас есть две чашки: в одной кофе, в другой чай. Поменяйте содержимое чашек местами.


using System;

namespace MyFirstApp
{
    class MainClass
    {
        public static void Main(string[] args)
        {
            string firsName = "Сайфутдинов";
            string lastName = "Айрат";

            Console.WriteLine($"Ваше имя: {firsName}");
            Console.WriteLine($"Ваша фамилия: {lastName}");

            (firsName, lastName) = (lastName, firsName);

            Console.WriteLine($"Ваше имя: {firsName}");
            Console.WriteLine($"Ваша фамилия: {lastName}");
        }
    }
}
