#include <iostream>
#include <cmath>
using namespace std;
int main() {
    double a, b;
    char c;
    cin>>a>>c>>b;
    switch (c) {
        case '+' :
            cout<<a+b<<endl;
            break;
        case '-';
            cout<<a-b<<endl;
            break;
        case '*':
            cout<<a*b<<andl;
            break;
        case '/':
            if (0 != b) {
                cout<<a/b<<endl;
            }else {
                cout<<"Error"<<endl;
            }
            break;
        default:
            cout<<"Wrong sign"<<endl;
    }
    return
}
