//program-penjumlahan c++
//Program di atas meminta pengguna untuk memasukkan dua bilangan dan kemudian menghitung jumlahnya. Hasil dari operasi penjumlahan kemudian dicetak ke layar.

#include <iostream>

using namespace std;

int main()
{
    int bilangan1, bilangan2, hasil;

    cout << "Masukkan bilangan pertama: ";
    cin >> bilangan1;

    cout << "Masukkan bilangan kedua: ";
    cin >> bilangan2;

    hasil = bilangan1 + bilangan2;

    cout << "Hasil dari " << bilangan1 << " + " << bilangan2 << " adalah " << hasil << endl;

    return 0;
}


