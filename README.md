# program10
# Latihan 1

```
txt = 'Hello World'

# Hitung jumlah karakternya
jumlah_karakter = len(txt)
print(jumlah_karakter)

# Ambil karakter terakhir
karakter_terakhir = txt[-1]
print(karakter_terakhir)

# Ambil karakter index ke-2 sampai index ke-4 (llo)
karakter_2_4 = txt[2:5]
print(karakter_2_4)

# Hilangkan spasi pada text tersebut (HelloWorld)
txt_tanpa_spasi = txt.replace(' ', '')
print(txt_tanpa_spasi)

# Ubah text menjadi huruf besar
txt_huruf_besar = txt.upper()
print(txt_huruf_besar)

# Ubah text menjadi huruf kecil
txt_huruf_kecil = txt.lower()
print(txt_huruf_kecil)

# Ganti karakter H dengan karakter J
txt_ganti_karakter = txt.replace('H', 'J')
print(txt_ganti_karakter)

![gambar1](https://user-images.githubusercontent.com/115562487/213173234-c3c26d03-51f4-4463-8b60-6cc5d66712fa.png)

# Latihan 2

```
umur = 24
txt = 'Hello, nama saya john, dan umur saya adalah {} tahun'
hasil = txt.format(umur)
print(hasil)

![gambar2](https://user-images.githubusercontent.com/115562487/213173590-0df516af-39cf-4d52-89e9-32ea784d72f6.png)

