# Kode Fungsi Alih Motor DC

Nama : Taritsa Tsalitsatus Sholihah
NIM : 235150301111023

## Langkah-langkah
1. **Model Matematika Motor DC**
    - Persamaan listrik: 
      $$V = Ri + L \frac{di}{dt} + T_m$$
    - Persamaan mekanik: 
      $$T_m = J \frac{d\omega}{dt} + b\omega$$

2. **Transformasi Laplace**
    - Transformasi persamaan listrik dan mekanik ke domain Laplace untuk mendapatkan hubungan antara kecepatan sudut ($\omega$) dan tegangan (V).

3. **Fungsi Alih**
    - Menentukan fungsi alih ($G(s)$) yang menghubungkan kecepatan sudut ($\omega$) dan tegangan (V).

## Import Library
Mengimpor library yang diperlukan untuk perhitungan simbolik dan transformasi Laplace.
```python
from sympy import symbols, Function, diff, Eq, dsolve, simplify, laplace_transform
