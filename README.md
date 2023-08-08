using System;

namespace IdadeFernanda
{
    class Program
    {
        static void Main()
        {
            int idadeCibele = int.Parse(Console.ReadLine());
            int idadeFernanda = int.Parse(Console.ReadLine());
            int idadeCeleste = int.Parse(Console.ReadLine());

            if (idadeCibele < idadeFernanda && idadeFernanda < idadeCeleste)
            {
                Console.WriteLine(idadeFernanda);
            }
            else if (idadeFernanda < idadeCibele && idadeCibele < idadeCeleste)
            {
                Console.WriteLine(idadeCibele);
            }
            else
            {
                Console.WriteLine(idadeCeleste);
            }
        }
    }
}
