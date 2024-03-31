# Program
```c++
#include <iostream>
using namespace std;

int main() {
    int matriks_a[2][2] = {{1, 2}, {3, 4}};
    int matriks_b[2][2] = {{5, 6}, {7, 8}};
    int hasil_jumlah[2][2];

    // Penjumlahan matriks
    for (int i = 0; i < 2; ++i) {
        for (int j = 0; j < 2; ++j) {
            hasil_jumlah[i][j] = matriks_a[i][j] + matriks_b[i][j];
        }
    }

    // Output matriks A
    cout << "Matriks A = " << endl;
    for (int i = 0; i < 2; ++i) {
        for (int j = 0; j < 2; ++j) {
            cout << matriks_a[i][j] << " ";
        }
        cout << endl;
    }
    cout << endl;

    // Output matriks B
    cout << "Matriks B = " << endl;
    for (int i = 0; i < 2; ++i) {
        for (int j = 0; j < 2; ++j) {
            cout << matriks_b[i][j] << " ";
        }
        cout << endl;
    }
    cout << endl;

    // Output hasil penjumlahan matriks A dan B
    cout << "Hasil penjumlahan matriks A dan B adalah = " << endl;
    for (int i = 0; i < 2; ++i) {
        for (int j = 0; j < 2; ++j) {
            cout << hasil_jumlah[i][j] << " ";
        }
        cout << endl;
    }

    return 0;
}
```
# Hasil Output

<img width="319" alt="Screenshot 2024-03-31 235753" src="https://github.com/alyanrni25/Tugas_1_AB1203/assets/156888432/2ff81049-58de-4086-89a4-e3e6b2e1d47e">
