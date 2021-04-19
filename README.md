#include <iostream>
using std::cout;
int main() {
    float a,c;
    char b;
    std::cin >> a >> b >> c;
    switch(b) {
        case '+': cout << a << b << c << '=' << a+c; break;
        case '-': cout << a << b << c << '=' << a-c; break;
        case '*': cout << a << b << c << '=' << a*c; break;
        case '/': cout << a << b << c << '=' << a/c;
    }
    return 0;
}
