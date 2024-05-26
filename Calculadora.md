
      //Calculadora em C++

#include <iostream>
    using namespace std;

    int main(){
    
    
    float num1,num2, total;
    int op;

    cout<< "digite um número:";
    cin>> num1;

    cout<< "digite um segundo número:";
    cin>> num2;

    cout << "qual operação vc quer realizar? \n ";
    cout<< "1 -  multiplicação \n ";
    cout<< " 2- adição \n ";
    cout<< "3- divisão \n ";
    cout<<"4- subtração \n ";
    cout<< "digite o número: ";
    cin>>op;

    if (op==1)
     {total= num1*num2;
     cout<< num1<<"*"<<num2<<"=" <<total;}
    
    else if (op==2)
     {total= num1+num2;
     cout<< num1<< "+" <<num2 <<"=" <<total;}

    else if (op==3)
    { total= num1/num2;
    cout << num1<<"/"<<num2<<"="<< total;}

    else if (op==4)
    { total= num1-num2;
    cout << num1<<"-"<<num2<<"="<<total;}

    else 
    {cout<< "opção inválida";}
}   