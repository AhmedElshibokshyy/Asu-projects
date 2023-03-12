#include <iostream>
#include <string.h>
using namespace std;
int main()  
{   
    string inputs;
    string R1;
    string R2;
    string R3;
    float Rt;
    float V;
    float I;
    cout << "Circuit Description: ";
    getline(cin, inputs);
    cout << "Voltage Applied: ";
    cin >> V;
    R1 = inputs[2];
    R2 = inputs[4];
    R3 = inputs[6];
    if(inputs[0] == 'S') {
        Rt = stof(R1) + stof(R2) + stof(R3);
        I = V/Rt;
        cout << I;
    }
     else if(inputs[0] == 'P') {
        (Rt) = ((1.0/(stof(R1))) + (1.0/(stof(R2))) + (1.0/(stof(R3))));
        I = V*Rt;
        cout << I;
    }
}
