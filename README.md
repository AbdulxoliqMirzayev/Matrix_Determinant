# Matrix_Determinant

#  NxN Matritsa: Determinant va Invers Hisoblash

Ushbu loyiha Python tilida yozilgan bo‘lib, foydalanuvchiga NxN o‘lchamdagi kvadrat matritsaning determinanti va teskari (invers) matritsasini **kutubxonalarsiz** hisoblash imkonini beradi. Har bir matematik qadam alohida funksiyalarda ifodalangan bo‘lib, kodni tushunishni va ta’limiy yondashuvni osonlashtiradi.


##  Maqsad
* Chiziqli algebra asoslarini amalda o‘rganish
* Minor, kofaktor, adjugat va determinant kabi tushunchalarni kod orqali mustahkamlash
* Junior (yangi boshlovchi) dasturchilar uchun rekursiya, matritsa elementlari bilan ishlash va algoritmik fikrlashni rivojlantirish

##  Asosiy funksiyalar

| Funksiya nomi       | Vazifasi                                                    |
| ------------------- | ----------------------------------------------------------- |
| `minor_matritsa()` | Minor matritsa (berilgan qator va ustunsiz kichik matritsa) |
| `determinant()`     | Matritsaning determinantini rekursiv hisoblaydi             |
| `kofaktorlar()`     | Har bir element uchun kofaktorlar matritsasini tuzadi       |
| `rotate()`        | Matritsani transponirlab adjugat holatiga keltiradi         |
| `invers()`          | Invers matritsani adjugat/determinant orqali hisoblaydi     |
| `chop_invers()`     | Invers natijani chiroyli formatda konsolga chiqaradi        |


## Foydalanish misoli

```python
matritsa = [
    [2, 1, 3],
    [1, 0, 2],
    [4, 1, 8]
]

chop_invers(matritsa)
```

**Chiqaradi:**

```
Invers matritsa:
[2.0, 5.0, -2.0]
[-0.0, -4.0, 1.0]
[-1.0, -2.0, 1.0]
```

---

## 📚 Qo‘shimcha o‘rganish manbalari

* [Math is Fun: Inverse of a Matrix](https://www.mathsisfun.com/algebra/matrix-inverse-minors-cofactors-adjugate.html)
* [arxiv.uz: Matritsa va determinantlar (O‘zbekcha PDF)](https://arxiv.uz/uz/documents/slaydlar/algebra/matritsa-va-determinantlar)
* [YouTube: Inverse of 3x3 Matrix](https://www.youtube.com/watch?v=pgqyULjZgbU)

---
