# Gün 4: Operatörler

Bugün öğrendiklerim:
- Aritmetik: `+ - * / %`. `%` bölümden kalanı verir (çift/tek kontrolünde işe yarar).
- İki `int` bölünürse küsurat atılır: `17 / 5 = 3`. Ondalıklı sonuç için birini `double` yapmalıyım.
- Karşılaştırma: `== != > < >= <=`, sonuç her zaman `true`/`false`.
- `=` atama, `==` karşılaştırma. `if (x = 5)` hata vermez ama yanlış çalışır.
- Mantıksal: `&&` (ve), `||` (veya), `!` (değil).
- Kısayollar: `+=`, `-=`, `++`, `--`.

```cpp
int hiz = 90;
bool kaskTakili = true;
bool guvenli = kaskTakili && hiz < 120;  // true
hiz += 10;                               // 100
```
