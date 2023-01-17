Nama : Rafif Isdarufa Athallah

NIM : 312210299

Kelas: TI.22.A3

---

## Latihan 1

![Latihan 1](https://user-images.githubusercontent.com/115514467/212912764-c7d5d18e-bb1d-44a0-82f7-56718351d360.jpg)

- Gunakan fungsi `len()` untuk menghitung panjang string
- Gunakan *indexing string* -> `...[-1]` untuk mengambil karakter terakhir pada string
- Gunakan *range of index* -> `...[2:5]` untuk melakukan *slicing* atau pemotongan string dari *index* ke-2 sampai *index* ke-4
- Gunakan fungsi `replace()` untuk mengganti kemunculan karakter substring tertentu dalam string dengan karakter substring baru
- Gunakan fungsi `upper()` untuk membuat semua karakter pada string menjadi huruf besar
- Gunakan fungsi `lower()` untuk membuat semua karakter pada string menjadi huruf kecil

```python
txt = "Hello World"

print(len(txt))
print(txt[-1])
print(txt[2:5])
print(txt.replace(" ", ""))
print(txt.upper())
print(txt.lower())
print(txt.replace("H", "J"))
```

Output:

```
11
d
llo
HelloWorld
HELLO WORLD
hello world
Jello World
```

---

## Latihan 2

![Latihan 2](https://user-images.githubusercontent.com/115514467/212912750-dccc7b57-91e7-4b05-8eff-b7f2b5061e3a.jpg)

- Untuk melengkapi kode tersebut, tambahkan kurung kurawal `{}` sebelum tahun

```python
umur = 24
txt = "Hello, nama saya John, dan umur saya adalah {} tahun"

print(txt.format(umur))
```

Output:

```
Hello, nama saya John, dan umur saya adalah 24 tahun
```

---

### Sekian, terimakasih
