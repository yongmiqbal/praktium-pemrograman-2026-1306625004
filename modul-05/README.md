# Modul [05] - [Program Sorting]

**Nama:** [Muhammad Iqbal]  
**NIM:** [1306625004]  
**Kelas:** [Fisika-C]  

---

## 1. Problem Statement
> Membuat  program yang dapat mensorting atau mengurutkan nilai input dari yang terkecil hingga yang terbesar

## 2. Mathematical Equation
> $$C(n) = \frac{n(n-1)}{2}$$$

## 3. Algorithm
> 1. Mulai
> 2. print"program sotring"
> 3. print"Muhammad Iqbal"
> 4. print"1306625004"
>> 1. while true
>> 2. try
>>> 1. input nilai
>>> 2. periksa nilai valid dengan valueerror
>>> 3. input valid?
>>>> 1. yes, break
>>>> 2. no, print"input tidak valid" return
> 5. inisialisasi i=0
> 6. while i<len(nilai)-1
>> 6.1. true
>>> 1. inisialisasi j
>>> 2. while j<nilai(len)-1-i
>>>> 1. true
>>>>> 1. if nilai [j] > nilai [j+1]
>>>>>> 1. if yes, nilai nilai [j] , nilai [j+1]= nilai [j+1] , nilai nilai [j]
>>>>>> 2. else, continue
>>>> 2. j = j+1
>>> 2. i = i+1
> 7. nilai terurut = join(str(angka) for angka in nilai)
> 8. print("\nNilai setelah diurutin : { }".Format (nilai_terurut))
> 9. print"Selesai"
> 10. selesai 
