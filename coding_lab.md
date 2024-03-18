# Menghitung Luas dan Keliling Persegi Panjang

```c++
#include <iostream>

int main() {
    float luas,keliling,panjang,lebar;

    std::cout << "Menghitung Luas dan keliling persegi panjang" << std::endl;
    std::cout << "Masukan panjang" << std::endl;
    std::cin >> panjang;
    std::cout << "Masukan lebar" << std::endl;
    std::cin >> lebar;
    luas=panjang*lebar;
    keliling=2*(panjang+lebar);

    std::cout << "luas persegi panjang: " << luas << std::endl;
    std::cout << "Keliling persegi panjang: " << keliling << std::endl;
    
    
    return 0;

}
```
# Screenshoot hasil running

![Screenshot 2024-03-18 084434](https://github.com/alyanrni25/Tugas_1_AB1203/assets/156888432/4fb7aad1-0b84-4438-83ca-e9019f1f4123)
