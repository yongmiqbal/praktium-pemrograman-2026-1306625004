# Modul [03] - [Trigonometri]

**Nama:** [Muhammad Iqbal]  
**NIM:** [1306625004]  
**Kelas:** [Fisika C]  

---

## 1. Problem Statement
> Membuat program untuk menghitung nilai sin dan cos dengan pendekatan deret Mc Laurin

## 2. Mathematical Equation
a. Deret Mclaurin untuk Sinus
> > $$\sin x = \sum_{n=0}^{\infty}\frac{(-1)^n x^{2n+1}}{(2n+1)!}$$

b. Deret Mclaurin untuk Cos
> > $$\cos x = \sum_{n=0}^{\infty}\frac{(-1)^n x^{2n}}{(2n)!}$$

## 3. Algorithm
> 1. Mulai
> 2. Import modul math.
> 3. Tampilkan judul program dan identitas pemilik program.
> 4. Definisikan fungsi sin_maclaurin(x):
> 4.1. Inisialisasi:
     - sin_x = 0
     - n = 0
     - er = 100
> 4.2. Selama er >= 5:
> 4.2.1. hitung suku ke-n dari deret Maclaurin:
> 4.2.2. suku = ((-1)^n * x^(2n+1)) / factorial(2n+1)
> 4.2.3. tambahkan suku ke sin_x
> 4.2.4. hitung nilai eksak sin(x)
> 4.2.5. hitung error: er = abs((nilai_eksak - sin_x) / nilai_eksak) * 100
> 4.2.5. naikkan n lalu Kembalikan sin_x dan er
> 5. Definisikan fungsi cos_maclaurin(x):
> 5.1. Inisialisasi:
     - cos_x = 0
     - n = 0
     - er = 100
> 5.2. Selama er >= 5:
> 5.2.1. hitung suku ke-n dari deret Maclaurin: suku = ((-1)^n * x^(2n)) / factorial(2n)
> 5.2.2. tambahkan suku ke cos_x
> 5.2.3. hitung nilai eksak cos(x)
> 5.2.4. hitung error: er = abs((nilai_eksak - cos_x) / nilai_eksak) * 100
> 5.2.5.naikkan n lalu Kembalikan cos_x dan er
> 6. Input masukkan sudut dalam derajat
> 7. Konversi sudut dari derajat ke radian: x = radians(derajat)
> 8. Panggil fungsi sin_maclaurin(x) dan cos_maclaurin(x)
> 9. Tampilkan hasil:
     - print ("nilai sin(x)")
     - print("error sin")
     - print("nilai cos(x)")
     - print("error cos")
> 10. Selesai

