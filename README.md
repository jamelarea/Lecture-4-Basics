# Lecture-4-C-Basics

EXERCISES 

SLIDE 18, Possible Data Types

    #include <iostream>
    #include <string>
    using namespace std;

    int main()
    {
        int firstNumber = 1; //integer
        bool iCanCode = true; //bool, declares a variable whose value will be set as true (1) or false (0)
        char hopefulGrade = 'a'; //character
        double myDecimal = 1.0; //holds numbers with decimal points
        string minimalSentence = "y"; //stores a sequence of letters or other characters
        int keyMash = 13213123; //integer
        float mysteryDataType = 5.6f; //used to define numeric values with floating decimal points

        return 0;
    }

SLIDE 21, Solution

    #include <iostream>
    using namespace std;

    int main()
    {
        double numberOne = 50;
        double numberTwo = 7;
        cout << numberOne / numberTwo << endl;

        cin.get(); //keeps console window open in Visual Studio

        return 0;
    }

SLIDE 23, USB Shopper

    #include <iostream>
    #include <string>
    using namespace std;

    int main()
    {
      //variables
      int money = 50;
      int cost = 6; 

      int canAfford = money / cost; //divides 50 (money) and 6 (cost)
      int remaining = 50 % 6; //remainder of 50 and 6

      cout << "she can afford " << canAfford << " usb sticks and have " << remaining << " remaining money left";

      return 0;
    }

SLIDE 24, Declaration and Initialisation

    #include <iostream>
    using namespace std;

    int main()
    {
        int numA = 6;
        int numB = 8;

        cout << numA + numB;

        return 0;
    }
