#include <iostream>
using namespace std;

int main()
{
    string first, second, resultant;

    cout << "Enter string first : ";
    getline (cin, first);

    cout << "Enter string second: ";
    getline (cin, second);

    resultant = first + second;

    cout << "Resulting String = "<< resultant;

    return 0;
}
