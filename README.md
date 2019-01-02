#include <iostream>
#include <conio.h>
#include <windows.h>

using namespace std;

int main()
{
    int bil1,bil2;
    cout<< " Masukkan bilangan pertama  :";
    cin>>bil1;
    cout<<endl;
    cout<< " Masukkan bilangan kedua    :";
    cin>> bil2;
    DOUBLE hasil=0;
    for (int i=1;i<=bil2;i++)
    {
        hasil=hasil+bil1;
    }
    cout<< "\t\t\t "<<bil1<< "  x "<<bil2<< " = "<<hasil<< " \n"<<endl;
    cout<< "\t\t---------------------------------------------\n"<<endl;
}
