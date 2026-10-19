# Gün 3: Girdi ve Çıktı (cin, cout)

Bugün öğrendiklerim:
- `cout <<` ekrana yazar, `cin >>` klavyeden okur. Okların yönü verinin akış yönü.
- `cin` okuduğu değeri değişkenin tipine göre otomatik çeviriyor (C#'taki gibi parse gerekmiyor).
- `cin >>` boşlukta durur. Boşluklu yazı okumak için `std::getline(std::cin, degisken)` kullanılır.

```cpp
std::string isim;
std::cout << "Adin ne? ";
std::cin >> isim;
std::cout << "Merhaba " << isim << std::endl;
```
