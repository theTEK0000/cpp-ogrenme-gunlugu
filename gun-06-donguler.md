# Gün 6: Döngüler (for, while)

Bugün öğrendiklerim:
- `for` kaç kere döneceği belli olduğunda kullanılır: başlangıç; şart; artış.
- `while` şart doğru olduğu sürece döner, kaç tur süreceği belli değilse kullanılır.
- `do-while` önce çalışır sonra şarta bakar, en az bir kere çalışır (menüler için ideal).
- `continue` o turu atlar, `break` döngüden tamamen çıkar.
- Şartı değiştiren bir şey yoksa sonsuz döngü olur.
- Arduino/ESP32'deki `loop()` aslında bilerek yapılmış sonsuz bir döngü.

```cpp
for (int i = 1; i <= 5; i++) {
    std::cout << i << ". tur" << std::endl;
}

int yakit = 10;
while (yakit > 0) {
    yakit -= 3;
}
```
