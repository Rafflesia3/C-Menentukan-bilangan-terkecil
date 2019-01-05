# C-Menentukan-bilangan-terkecil

    #include <iostream>
    #include <conio.h>

    using namespace std;

    int main()
    {
    cout << "\t\t Pelita Bangsa \n\n" << endl;
    cout << "=========================================\n" << endl;
    cout << "Nama    : Rafi Alwan Setyawan \nNIM     : 311810325 \nKelas   : TI.18.D7 \n" << endl;
    cout << "=========================================\n" << endl;

    cout<< "\t     Menentukan bilangan terkecil dari 3 buah bilangan\n" << endl;

    int a,b,c,x;
    cout<<"Masukan A: ";cin>>a;
    cout<<"Masukan B: ";cin>>b;
    cout<<"Masukan C: ";cin>>c;

    if(b < a)
    {
        x=b;
        b=a;
        a=x;
    }
    if(c < a)
    {
        x=c;
        c=a;
        a=x;
    }
    if(c < b)
    {
        x=b;
        b=c;
        c=x;
    }
    cout<<"Jadi Bilangan yang terkecil adalah : "<<a;
    cout<<"\ndan Berikut adalah urutan bilangan dari yang terkecil : "<<a<<" , "<<b<<" , "<<c;

    getch();
    }
    
Hasil
![img](https://github.com/Rafflesia3/C-Menentukan-bilangan-terkecil/blob/master/C++%20Menampilkan%20bilangan%20terkecil%20dari%203%20buah%20bilangan.png?raw=true)
