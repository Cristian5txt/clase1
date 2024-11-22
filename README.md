#include <iostream>

using namespace std;

int main()

{
    int a, b, c, R1, R4;
    bool R2,R3,R5,R6,R7,R8;

    cout << "INGRESE EL VALOR DE a" << endl;
    cin>> a;
    cout << "INGRESE EL VALOR DE b" << endl;
    cin>>b;
    cout << "INGRESE EL VALOR DE c" << endl;
    cin>>c;

    R1 = (a+b);
    R2 = (R1==c);
    R3 = (c!=0);
    R4 = (b-c);
    R5 = (R5>=19);
    R6 = !R2;
    R7 = (R3&&R5);
    R8 = (R6 || R7);

    cout<< "R1 ES "<<R1<<endl;
    cout<< "R2 ES "<<R2<<endl;
    cout<< "R3 ES "<<R3<<endl;
    cout<< "R4 ES "<<R4<<endl;
    cout<< "R5 ES "<<R5<<endl;
    cout<< "R6 ES "<<R6<<endl;
    cout<< "R7 ES "<<R7<<endl;
    cout<< "R8 ES "<<R8<<endl;
    return 0;
}
