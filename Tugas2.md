# Program
```c++
#include <iostream>
#include <string>
#include <map>

std::string haribesok(const std::string& hari_sekarang) {
    std::map<std::string, std::string> hari = {
        {"senin", "selasa"}, {"selasa", "rabu"}, {"rabu", "kamis"}, {"kamis", "jumat"}, {"jumat", "sabtu"}, {"sabtu", "minggu"}, {"minggu", "senin"}
    };
    auto it = hari.find(hari_sekarang);
    if (it != hari.end()) {
        return it->second;
    }
    std::cout << "Hari yang salah: " << hari_sekarang << std::endl;
    return "";
}
int main() {
    std::string hari_sekarang;
    std::cout << "Masukan nama hari dalam seminggu (senin-minggu): ";
    std::cin >> hari_sekarang;
    std::string hari_besok = haribesok(hari_sekarang);
    if (!hari_besok.empty()) {
        std::cout << "Hari selanjutnya adalah: " << hari_besok << std::endl;
    }
    return 0;
}
```
# Screenshhot

<img width="371" alt="Screenshot 2024-03-23 175031" src="https://github.com/alyanrni25/Tugas_1_AB1203/assets/156888432/4e0aa080-8632-492a-b0e6-7a54e098ae0e">


