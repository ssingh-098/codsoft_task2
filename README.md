//Task-2(Simple calculator)

#include<iostream>
using namespace std;
int main()
{
    char ch;
    int a,b;
    cout<<"enter the operator";
    cin>>ch;
    cout<<"enter the two operands";
    cin>>a>>b;
    switch (ch)
    {
    case '+':cout<<a<<" "<<ch<<" "<<b<<" "<<'='<<" "<<a+b;
    break;
    case '-':cout<<a<<" "<<ch<<" "<<b<<" "<<'='<<" "<<a-b;
    break;
    case '*':cout<<a<<" "<<ch<<" "<<b<<" "<<'='<<" "<<a*b;
    break;
    case '/':cout<<a<<" "<<ch<<" "<<b<<" "<<'='<<" "<<a/b;
    break;
    default: cout<<"invalid input!";
    }
    return 0;
}
