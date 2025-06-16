# Automata Theory Final Project: The Busy Beaver
![image](https://github.com/user-attachments/assets/605834e7-c3b9-41a8-b9a7-3756f388f1b8)

*Why is The Beaver Busy?*

# Otomata E - Kelompok 6
| Nama | NRP |
|----------|----------|
| Achmad Hasan Al Fikri | 5025231052 |
| Zaky Fathurrahman | 5025231105 |
| Muhammad Khibban I'tishom | 5025231126 |
| Richard Hans Ng | 5025231180 |

# Chapter I: Mesin Turing
Mesin Turing adalah model komputasi teoritis yang menggambarkan mesin abstrak yang memanipulasi simbol pada suatu pita menurut tabel aturan. Mesin ini beroperasi pada pita dengan memori tak terbatas yang dibagi menjadi sel-sel diskrit, yang masing-masing dapat menyimpan satu simbol yang diambil dari sekumpulan simbol terbatas yang terdaftar pada mesin. Mesin ini memiliki _head_ yang, pada titik mana pun dalam operasi mesin, diposisikan di atas salah satu sel ini, dan _state_ yang dipilih dari sekumpulan _state_ yang terbatas.

Pada setiap langkah operasinya, _head_ membaca simbol dalam selnya. Kemudian, berdasarkan simbol dan keadaan mesin saat ini, mesin menulis simbol ke dalam sel yang sama, dan menggerakkan head satu langkah ke kiri atau ke kanan, atau menghentikan penghitungan. Pilihan simbol pengganti mana yang akan ditulis, ke arah mana untuk menggerakkan kepala, dan apakah akan berhenti didasarkan pada tabel berhingga yang menentukan apa yang harus dilakukan untuk setiap kombinasi keadaan saat ini dan simbol yang dibaca.

Dalam konteks bahasa formal, Mesin Turing mampu membuat daftar sebagian himpunan sembarang dari string-string valid dalam suatu alfabet. Himpunan string yang dapat didaftar dengan cara ini disebut sebagai bahasa yang dapat dihitung secara rekursif. Mesin Turing juga dapat didefinisikan secara ekuivalen sebagai model yang mengenali string input yang valid, bukan menghasilkan string output. Mesin Turing juga mampu memproses _Unrestricted Grammar_, yang berarti bahwa mesin ini mampu mengevaluasi _First-Order Logic_ secara tangguh dalam jumlah cara yang tak terbatas. Hal ini secara terkenal ditunjukkan melalui kalkulus lambda.

Anggap jika kita memiliki sebuah mesin Turing `M` dan sebuah string sembarang `s`, secara umum tidak mungkin untuk memutuskan apakah `M` pada akhirnya akan menghasilkan `s`. Hal ini disebabkan oleh fakta bahwa _halting problem_ tidak dapat diselesaikan, yang memiliki implikasi besar terhadap batas teoretis dari komputasi.
