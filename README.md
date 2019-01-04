# Program-Pengecek-Bilangan-Prima
    #include <iostream>
    #include <conio.h>

    using namespace std;
    int main()
    {
    int bil, jum, i;
    cout << "Masukkan bilangan bulat positif : ";
    cin >> bil;
    jum = 0;
    for (i=1; i<=bil; i++)
    if (bil%i==0)
    jum++;
    if (jum==2)
    cout << "Bilangan tersebut adalah bilangan prima \n";
    else
    cout << "Bukan bilangan prima \n";
    return 0;
    }
   ![img](https://raw.githubusercontent.com/BambangPriam/Program-Pengecek-Bilangan-Prima/master/Pengecek%20Bilangan%20Prima.png)
