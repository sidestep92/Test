#include <iostream>

using namespace std;

void functionone();
void functiontwo();
void functionthree();

int main()
{
    char number;
    cout << "Enter a number: ";
    cin >> number;

    if (number == '1')
    {
        functionone();
    }
    else if (number == '2')
    {
        functiontwo();
    }
    else
    {
        functionthree();
    }


}

void functionone()
{
    cout << "You have entered number 1! You rock!" << endl;
}

void functiontwo()
{
    cout << "You have entered number 2! You are not that great anymore!" << endl;
}

void functionthree()

{
    cout << "You have not been a good person! You disobeyed our requests!" << endl;
}
