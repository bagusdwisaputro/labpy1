#labpy1

# ==PROGRAM SEDERHANA MENENTUKAN BILANGAN TERBESAR DARI 3 BILANGAN==

## Algoritma menentukan bilangan terbesar:

1.Masukkan bilangan pertama (a)

2.Masukkan bilangan kedua (b)

3.Masukkan bilangan ketiga (c)

4.Jika a lebih dari b dan a lebih dari c, maka bilangan terbesar adalah a

5.Jika b lebih dari c dan b lebih dari a, maka bilangan terbesar adalah b

6.Jika pernyataan 4 dan 5 salah, maka bilangan terbesar adalah c

## Flowchart =>

<img width="192" alt="flowchart" src="https://user-images.githubusercontent.com/47028610/52731737-10fab380-2ff1-11e9-8a0e-16e449deb7ad.png">

## Program 

  print ("==PROGRAM SEDERHANA MENENTUKAN BILANGAN TERBESAR DARI 3 BILANGAN==")
  a = int(input("Masukkan bilangan 1:"))
  b = int(input("Masukkan bilangan 2:"))
  c = int(input("Masukkan bilangan 3:"))

  if a>b and a>c:
      print ("Bilangan terbesar adalah :",a)
  if b>a and b>c:
     print ("Bilangan terbesar adalah :", b)
  else :
     print ("Bilangan terbesar adalah :",c)
    
   <img width="960" alt="program" src="https://user-images.githubusercontent.com/47028610/52731925-86668400-2ff1-11e9-85d6-7ee6c2557d84.png">
    
 # penjelasan==>>
 1. Akan menampilakan kalimat "==PROGRAM SEDERHANA MENENTUKAN BILANGAN TERBESAR DARI 3 BILANGAN=="
 2. a adalah perwakilan sebuah data inputan bilangan pertama yang bersifat bilangan bulat
 3. b adalah perwakilan sebuah data inputan bilangan kedua yang bersifat bilangan bulat
 4. c adalah perwakilan sebuah data inputan bilangan ketiga yang bersifat bilangan bulat
 5. pernyataan yang menyatakan "Jika a lebih besar dari b dan a lebih besar dari c
 6. jika pernyataan 5 benar, maka akan menampilkan data a
 7. pernyataan yang menyatakan "Jika b lebih besar dari a dan b lebih besar dari c
 8. jika pernyataan 7 benar, maka akan menampilkan data b
 9. Pernyataan jika pernyataan 5 dan 7 salah
 10. Maka akan menampilkan data c
  
  # Menjalankan program
  
  <img width="960" alt="program" src="https://user-images.githubusercontent.com/47028610/52731925-86668400-2ff1-11e9-85d6-7ee6c2557d84.png">

   kita masukkan bilangan pertama :65
   kita masukkan bilangan kedua :456
   kita masukkan bilangan ketiga :8
   maka pernyataan no.5 salah
   pernyataan no.7 benar (b>a dan b>c)
   maka akan menampilkan data b (456)
    
    
Penjelasan program :
-print()     =>Fungsi untuk menampilan suatu output

-" "         =>Deklarasi data adalah data string(huruf/kalimat)

-int         =>(integer) type data untuk mendeklarasikan untuk type data bilangan bulat

-input       =>Fungsi untuk memasukkan suatu data

-if          =>operator yang mengecek pernyataan yang telah diinputkan

-else        =>operator yang menerima nilai jika pernyataan if tidak benar

# Nama  :Bagus Dwi Saputro
# NIM   :311810029
# Kelas :18 TI B1

