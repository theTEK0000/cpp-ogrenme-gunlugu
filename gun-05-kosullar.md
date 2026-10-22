# Gün 5: Koşullar (if, else, switch)

Bugün öğrendiklerim:
- `if / else if / else` yukarıdan aşağı kontrol edilir, ilk doğru olan çalışır.
- `switch` bir değişkeni sabit değerlerle karşılaştırır. `default` hiçbiri tutmazsa çalışır.
- C++'ta `break` unutulursa hata vermez, alttaki case'e düşer (fall-through). C#'ta hata verirdi.
- C++'ta `switch` string ile çalışmaz. Sadece int, char, enum gibi tiplerle çalışır.
- Kısa if: `kosul ? dogruysa : yanlissa`

```cpp
if (hiz > 120) {
    std::cout << "Yavasla!";
} else {
    std::cout << "Normal hiz.";
}

std::string durum = (hiz > 120) ? "Hizli" : "Normal";
```
