# Modul [01] - [Tabel Konversi Suhu Celcius – Reamur – Fahrenhei]

**Nama:** [Muhammad Iqbal]  
**NIM:** [1306625004]  
**Kelas:** [FISIKA-C]  

---

## 1. Problem Statement
> Membuat sebuah program untuk membuat "Tabel Konversi Suhu Celcius – Reamur – Fahrenheit" denga memberikan input kemudian program bekerja dengan mengkonversikan suhu Celcius menjadi reamur & fahrenheit atau sebaliknya.

## 2. Mathematical Equation
> $${}^\circ F = \frac{9}{5}C + 32$$
> $${}^\circ R = \frac{4}{5}{}^\circ C$$

## 3. Algorithm
> 1. Mulai
> 2. prinnt"Program Konversi Suhu"
> 3. Print "Nama: Muhammad Iqbal"
> 4. Print "NIM:1306625004"
> 5. Input  "Suhu Awal:..."
> 6. Input "Suhu Akhir:..."
> 7. print(f"{'Celcius':<12} | {'Fahrenheit':<15} | {'Reamur':<10}")
> 8. print("-" * 50)
> 
> 9A. if Suhu_Celcius_Awal <= Suhu_Celcius_Akhir:
>     Maka: for Suhu_Celcius in range(int(Suhu_Celcius_Awal), int(Suhu_Celcius_Akhir) + 1, 10): (10A in loop)
>
> 10A.
>    - Hitung Celcius ke Reamur : (Rumus C -> R)
>    - Hitung Celcius ke Fahrenheit : (Rumus C -> F)
>    - Suhu_Celcius + 1
>
> 9B. Jika tidak, for Suhu_Celcius in range(int(Suhu_Celcius_Awal), int(Suhu_Celcius_Akhir) - 1, -10): (10B in loop)
> 10B.
>    - Hitung Celcius ke Reamur : (Rumus C -> R)
>    - Hitung Celcius ke Fahrenheit : (Rumus C -> F)
>    - Suhu_Celcius - 1
> 
> 11. False Outloop, print(f"{Suhu_Celcius:<12} | {Fahrenheit:<15.2f} | {Reamur:<10.2f}")
> 12. Print ("Selesai")
> 13. Selesai

## 4. FLOWCHART
