# Given two numbers a and b, you need to swap their values so a holds the value of b and b holds the value of a. Just write the code to swap values of a and b at the specified place.

## C++:
#include <iostream>
using namespace std;

int main() {
    int a, b;
    cin >> a >> b;
    int temp;
    temp =a;
    a = b;
    b = temp;
    cout << a << " " << b << endl;
    return 0;
}
