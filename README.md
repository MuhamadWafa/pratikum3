# BIODATA
# NAMA  : MUHAMAD WAFA MUFIDA ZULFI
# KELAS : TI.24.A4
# NIM   : 312410334
# MATKUL: BAHASA PEMOGRAMAN

![WhatsApp Image 2024-10-20 at 10 55 01_a29547f6](https://github.com/user-attachments/assets/68674815-7eae-4d1a-b380-f2d1dae8b950)

# PRAKTIKUM 3
# LATIHAN 1

![WhatsApp Image 2024-10-20 at 14 26 18_a82c4f79](https://github.com/user-attachments/assets/0f574ab6-80a5-49a4-afc7-fd4b0418fbed)

# PEMBAHASAN MENGENAI :
# PENGGUNAAN AKHIR 
# PENGGUNAAN SEREPATOR
# BENTUK STRING
# PENGGUNAAN AKHIR

![WhatsApp Image 2024-10-20 at 14 27 49_9caf21d0](https://github.com/user-attachments/assets/8c582d89-2a08-424c-9586-5c88df4237e6)

```PYTHON
print('A', end='')
print('b', end='')
print('c', end='')
print()
print('x')
print('y')
print('z')
````

Parameter end dalam fungsi Print() di python digunakan untuk menambahkan string(" ")apapun diakhir dan mengeluarkan pertanyaan print

```PYTHON
Print()
````
Secara default,fungsi print() akan berakhir dengan baris baru,dan akan secara otomatis karakter baris baru di akhir outputnya
inilah hasil program tersebut:

![WhatsApp Image 2024-10-20 at 14 45 20_8564751e](https://github.com/user-attachments/assets/09faa6ef-e7d7-4573-a214-0f04f3e5850d)

dan ini hasil tanpa menggunakan fungsi print() di tengah pada kode program di atas:

![WhatsApp Image 2024-10-20 at 14 45 30_d59d567c](https://github.com/user-attachments/assets/27755aff-3764-4ed2-b870-e8522c430706)

# PENGGUNAAN SEREPATOR

![WhatsApp Image 2024-10-20 at 14 27 59_d7059aa5](https://github.com/user-attachments/assets/a6677ea6-40a9-4573-a9c4-5e9646933672)

```PYTHON
w, x, y, z, =10, 15, 20, 25
print(w, x, y, z,)
print(w, x, y, z, sep=',')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='-----')
````

pada python penggunaan serepator dapat menggunakan fungsi split() atau sep yang seperti dalam kode program di atas

serepator ini menentukan yang digunakan untuk memisahkan sting,serepator dapat berupa karakter tunggal atau beberapa karakter.jika tidak ditentukan,maka python akan menggunakan spasi sebagai pemisah.

Berikut Hasil Kode Program Diatas:

![WhatsApp Image 2024-10-20 at 14 56 38_fec5a7eb](https://github.com/user-attachments/assets/42914762-33ba-4c55-8d22-6094d49ff177)

```PYTHON
w, x, y, z, =10, 15, 20, 25
````

Variabel yang seperti ini menentukan parameter,jadi variabel ini tidak bisa memasukan variabel angka yang sudah ditentukan w = 10,x=15,y=20,z=25

```PYTHON
print(w, x, y, z,)
````

Fungsi ini hanya mencetak saja yang menggunakan fungsi print(), tetapi karena parameter pencetakan,koma tersebut hilangkan

```PYTHON
print(w, x, y, z, sep=',')
````

karena pemisahannya dihilangkan,kita menggunakan fungsi sepatausplit()dan kita memasukkan pemisahnya ke dalam string akan memunculkan cetakan yang sesuai keinginan anda dalam memisahkan sesuatu parameter

# BENTUK STRING

![WhatsApp Image 2024-10-20 at 15 05 47_b2d94640](https://github.com/user-attachments/assets/94a75d29-3ee6-4d43-a865-419ffe6337f8)

```PYTHON
print(0, 10**0)
print(1, 10**1)
print(2, 10**2)
print(3, 10**3)
print(4, 10**4)
print(5, 10**5)
print(6, 10**6)
print(7, 10**7)
print(8, 10**8)
print(9, 10**9)
print(10, 10**10)

print('{0:>3} {1:>16}'.format(0, 10**0))
print('{0:>3} {1:>16}'.format(1, 10**1))
print('{0:>3} {1:>16}'.format(2, 10**2))
print('{0:>3} {1:>16}'.format(3, 10**3))
print('{0:>3} {1:>16}'.format(4, 10**4))
print('{0:>3} {1:>16}'.format(5, 10**5))
print('{0:>3} {1:>16}'.format(6, 10**6))
print('{0:>3} {1:>16}'.format(7, 10**7))
print('{0:>3} {1:>16}'.format(8, 10**8))
print('{0:>3} {1:>16}'.format(9, 10**9))
print('{0:>3} {1:>16}'.format(10, 10**10))
````

String Format adalah proses memasukan variabel atau string kustom ke dalam teks yang sudah ditentukan, dan dapat digunakan untuk berbagai keperluan, seperti memasukan judul dalam grafik, menampilkan pesan atau kesalahan, atau meneruskan kesalahan ke suatu fungsi

```PYTHON
print(0, 10**0)
print(1, 10**1)
print(2, 10**2)
print(3, 10**3)
print(4, 10**4)
print(5, 10**5)
print(6, 10**5)
print(8, 10**8)
print(9, 10**9)
print(10, 10**10)
````

Nilai pertama dalam setiap pasangan adalah angka dari 0 hingga 10, kode program ini dihitung dengan menggunakan operasi pangkat atau fungsi () untuk menaikkan 10 ke pangkat yang sesuai dengan pertama, yang bisa dalam bahasa manusia angkakan variabel 0 = 10 pangkat 0, variabel 1 10 Pangkat 1 dan seterusnya hingga variabel 10 yaitu 10 pangkat 10, dan di cetak dengan fungsi print()

```PYTHON
print('{0:>3} {1:>16}'.format(0, 10**0))
print('{0:>3} {1:>16}'.format(1, 10**1))
print('{0:>3} {1:>16}'.format(2, 10**2))
print('{0:>3} {1:>16}'.format(3, 10**3))
print('{0:>3} {1:>16}'.format(4, 10**4))
print('{0:>3} {1:>16}'.format(5, 10**5))
print('{0:>3} {1:>16}'.format(6, 10**6))
print('{0:>3} {1:>16}'.format(7, 10**7))
print('{0:>3} {1:>16}'.format(8, 10**8))
print('{0:>3} {1:>16}'.format(9, 10**9))
print('{0:>3} {1:>16}'.format(10, 10**10))
````

Kode ini mencetak 11 baris dengan format {0:3} {1:16} yang digunakan untuk mengatur format string

Pada string pertama, angka 0 di format untuk memeliki lebar 3 karakter atau yang bisa disebut 3 kali spasi dengan peran kanan.

angka 1 diformat untuk memiliki lebar 16 Karakter atau 16 kali spasi dengan peran kanan, dan masing-masing mencetak nilai seperti format di atas dengan fungsi print()

# KODE PROGRAM
# 3 INPUT BILANGAN

```PYHTON
a = int(input("masukan angka pertama: "))
b = int(input("masukan angka kedua: "))
c = int(input("masukan angka ketiga: "))

if a > b and a > c:
    print(f"angka lebih besar adalah {a}")
elif b > a and b > c:
    print(f"angka lebih besar adalah {b}")
else:
    print(f"angka lebih besar adalah {c}")
````

Program ini akan menginputkan 3 bilangan dari a yang sampai dengan c.

```PYHTON
if a > b and a > c:
    print(f"angka lebih besar adalah {a}")
````

Karna Jika {a} lebih besar dari {b} dan {a} lebih besar dari {c}, keluaran yang keluar adalah {a}

```PYHTON
elif b > a and b > c:
   print(f"angka lebih besar adalah {b}")
````

dan jika {b} lebih besar dari {a} dan {b} lebih besar dari {c} maka output yang keluar adalah {b}

```PYHTON
else:
    print(f"angka lebih besar adalah {c}")
````

Jika inputan yang diatas lebih kecil dari {c} maka output {c} yang akan keluar

Ini adala hasil program tersebut :

![WhatsApp Image 2024-10-21 at 19 40 20_29949255](https://github.com/user-attachments/assets/9481c21e-dc23-4bef-9470-d3ad28abe1d7)

dengan program eksekusi:

<img width="960" alt="Screenshot 2024-10-21 180951" src="https://github.com/user-attachments/assets/dabc21af-be4a-43ce-88f9-cba79e760619">

dan diagram alur sebagai berikut:

![GARCIA FLOWCHART](https://github.com/user-attachments/assets/5808aacb-6633-4284-b06e-4adb7d197671)












