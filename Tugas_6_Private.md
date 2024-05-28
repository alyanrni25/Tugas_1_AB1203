# Tugas 6
## 1. OOP Robot
Program :
```c++
#include <iostream>
using namespace std;

class Robot {
private:
    string nama, mbti;
    int umur;

public:
    Robot(string n, int u, string m) {
        nama = n;
        umur = u;
        mbti = m;
    }

    void tampilkan_info() {
        cout << "Nama: " << nama << endl;
        cout << "Umur: " << umur << endl;
        cout << "MBTI: " << mbti << endl;
    }
};

int main() {
    Robot prototipe1("Ucil", 20, "ISTJ");

    prototipe1.tampilkan_info();

    Robot prototipe2("Molli", 10, "IFNJ");

    prototipe2.tampilkan_info();

    return 0;
}
```
Screenshoot Output:

![Screenshot 2024-05-29 030944](https://github.com/alyanrni25/Tugas_1_AB1203/assets/156888432/5c2f007d-467e-4ebc-b933-f799c2189525)

## 2. OOP Jam Tangan
Program :
```c++
#include <iostream>
using namespace std;

class JamTangan {
private:
    string merk;
    string model;
    string warna;
    float harga;

public:
    JamTangan(string m, string mo, string w, float h) {
        merk = m;
        model = mo;
        warna = w;
        harga = h;
    }

    void tampilkan_info() {
        cout << "Merk: " << merk << endl;
        cout << "Model: " << model << endl;
        cout << "Warna: " << warna << endl;
        cout << "Harga: Rp" << harga << endl;
    }

    float hitung_harga_diskon(float persen) {
        return harga - (harga * persen / 100);
    }

    void tampilkan_harga_diskon(float persen) {
        float harga_diskon = hitung_harga_diskon(persen);
        cout << "Harga setelah diskon " << persen << "%: Rp" << harga_diskon << endl;
    }
};

int main() {
    JamTangan jam1("Rolex", "Submariner", "Hitam", 15000000);

// Contoh diskon 10%
    jam1.tampilkan_info();
    jam1.tampilkan_harga_diskon(10);  

    JamTangan jam2("Seiko", "Prospex", "Biru", 5000000);

// Contoh diskon 15%
    jam2.tampilkan_info();
    jam2.tampilkan_harga_diskon(15);  

    return 0;
}
```
Screenshoot Ouput :

![Screenshot 2024-05-29 031244](https://github.com/alyanrni25/Tugas_1_AB1203/assets/156888432/bc96741e-8224-4de4-a7f3-b8ef97851b63)



