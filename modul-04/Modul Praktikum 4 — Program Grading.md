# Modul [04] - Program Grading

**Nama:** [Muhammad Iqbal] 
**NIM:** [1306625004]  
**Kelas:** [FISIKA C]  

---

## 1. Problem Statement
> Program yang dapat melakukan grading total dari nilai harian, PTS, UTS, dan penilaian lainnya seperti di excell misal bila dapat nilai 30 dapetnya d dan nilai 90 dapetnya A

## 2. Mathematical Equation
> NA = 30% × Nilai Lain2 + 35% × UTS + 35% × UAS

## 3. Algorithm
> 1. Mulai
> 2. print"program grading nilai"
> 3. print identitas "Muhammad Iqbal , 1306625004"
> 4. input jumlah mahasiswa
> 5. input nama mahasiswa sejumlah variabel jumlah_mahasiswa
> 6. input nilai lain 4 mahasiswa dst jika jumlah mahasiswa lebih
> 7. input nilai UTS 4 mahasiswa dst jika jumlah mahasiswa lebih
> 8. input nilai UAS CTH input (8090796896) 4 mahasiswa dst jika jumlah mahasiswa lebih
> 9. Membuat lisy data_akhir [nama mahasiswa, nilai akhir, grading]
> 10. insialiasi nomor kategori = 0
> 11. nomor kategori in range0, jumlah_mahasiswa
> 11. 1. while true
>     2. 1. append nama mahasiswa [nomor_kategori]
>        2. nilai 1 = nilai lain [nomor_kategori] *0,30
>        3. nilai 2 = nilai UTS [nomor_kategori] * 0,35
>        4. nilai 3 = nilai UAS [nomor_kategori] * 0,35
>        5. nilai akhir = nilai 1 + nilai 2 + nilai 3
>        6. Append nilai akhir
>        7. if nilai akhir >= 86, grade"A"
>        7. 1. else nilai akhir >= 81, grade "A-"
>           2. else nilai akhir >= 76, grade "B+"
>           3. else nilai akhir >= 71, grade "B"
>           4. else nilai akhir >= 66, grade "B-"
>           5. else nilai akhir >= 61, grade "C+"
>           6. else nilai akhir >= 56, grade "C"
>           7. else nilai akhir < 56, grade "TL"
>        8. Append grade
>        9. nomor_kategori = nomor kategori+1
>      3. False, outloop
> 12.  inisialisasi NO = 0
> 13.  ciptakan tabel
> 14.  while NO <= jumlah mahasiswa?
> 14. 1. while true
>     2. 1. print "Format( {NO+1} {Nama_Mahasiswa [NO]} {Nilai_Akhir [NO]} {grading [NO]}
>        2. NO = NO+1
>     3. false outloop
> 15. print "jumlah mahasiswa: , Jumlah_mahasiswa
