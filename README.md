            //task 9
            Console.WriteLine("How much boxes you buy?");
            int a = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("How much boxes you sell?");
            int b = Convert.ToInt32(Console.ReadLine());

            if(b * 10 > a * 5)
            {
                Console.WriteLine("you earn" + (b * 10 - a * 5));

            }
            else
                Console.WriteLine("you lose" + (b * 10 - a * 5));



            //task 10
            Console.WriteLine("How much pupils in yud1");
            int yud1 = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("How much pupils in yud2");
            int yud2 = Convert.ToInt32(Console.ReadLine()); 
            Console.WriteLine("How much pupils in yud1");
            int yud3 = Convert.ToInt32(Console.ReadLine());

            Console.WriteLine("you need buses:" + ((yud1 + yud2 + yud3) / 40));


            //task 11
            Console.WriteLine("what your theudat zeut?");
            int zeut = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("what you speed:");
            int currentSpeed = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("what is the legal speed:");
            int legalSpeed = Convert.ToInt32(Console.ReadLine());
            if(currentSpeed > legalSpeed)
            {
                Console.WriteLine("your teudat zeut" + zeut);

            }
            else
            {
                Console.WriteLine("all good");
            }

            //task 12
            Console.WriteLine("type operator");
            char oper = Convert.ToChar(Console.ReadLine());
            Console.WriteLine("first num");
            int num1 = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("second num");
            int num2 = Convert.ToInt32(Console.ReadLine());

            if(oper == '+')
                Console.WriteLine(num1 + num2);
            else if(oper == '-')
                Console.WriteLine(num1 - num2);
            else if (oper == '*')
                Console.WriteLine(num1 * num2);
            else if (oper == '/')
                Console.WriteLine(num1 / num2);

            //task 14   
            Console.WriteLine("type an number with 3 numbers");
            string num = Console.ReadLine();
            if (num[0] == num[2])
                Console.WriteLine("the num is palindrom");
            else
                Console.WriteLine("the num isnt palindrom");
