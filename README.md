# meetgithub
My first github repository file.
<br>
Author-Md.Foysal Kabir Digonto
<br>
<br>
From here the codes i have practiced so far...
<br>
<br>
1.//Write a C++ program that prints all the odd numbers in the range from 1 to 100 using a loop.
<br>

#include<iostream>
<br>
#include <conio.h>
<br>
using namespace std;

int main()
{

    for (int i = 1; i <= 100; i++)
    {
            if (i % 2 != 0)
            {
            cout << i << " ";
            }

    }
    getch();
}

2.//C++ program that: Takes an input number from the user. Checks every number from
//1 to that number and: If the number is divisible by 3, print "Fizz". If the number is
//divisible by 5, print "Buzz". If the number is divisible by both 3 and 5, print
//"FizzBuzz". Otherwise, print the number itself.
<br>
#include <.iostream>
using namespace std;

int main(){
<br>
    int n;

    cout << "Enter a number: ";
    cin >> n;

    for (int i = 1; i <= n; i++)

        {

        if (i % 3 == 0 && i % 5 == 0)
        {
            cout << "FizzBuzz" << endl;
        }
      else if (i % 3 == 0)
        {
            cout << "Fizz" << endl;
        }
        else if (i % 5 == 0)
        {
            cout << "Buzz" << endl;
        }
        else
        {
            cout << i << endl;
        }
    }

    return 0;
}


