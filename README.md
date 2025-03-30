# 000000
int a, s;
            a = int.Parse(Console.ReadLine());
            if (a <= 5)
            {
                s = 0;
            }
            else if (a <= 20)
            {
                s = (a - 5) * 1000;
            }
            else
            {
                s = 15 * 1000 + (a - 20) * 5000;
            }
            s = s + 10000;
            Console.WriteLine(s);
