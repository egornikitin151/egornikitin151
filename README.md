//
//  main.cpp
//  c++ osnovy algoritm
//
//  Created by Егор Никитин on 04.10.2022.
//

#include <iostream>
#include <cmath>
using namespace std;
int main()
{
    int a,b,c,P;
    cout << "katet 1: ";
    cin >> a;
    cout << "katet 2: ";
    cin >> b;
    c = a * a + b * b;
    c = sqrt(c);
    cout << "hipotenysa =" << c;
    P = a + b + c;
    cout << "perimetr = " <<P;
    
    
    return 0;
}

--->
