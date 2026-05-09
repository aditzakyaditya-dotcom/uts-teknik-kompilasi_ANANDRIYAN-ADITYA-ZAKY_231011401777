# uts-teknik-kompilasi_ANANDRIYAN-ADITYA-ZAKY_231011401777
Tugas UTS Teknik Kompilasi 

# Tugas UTS Teknik Kompilasi

## Nama
ANANDRIYAN ADITYA ZAKY

## NIM
231011401777


# Jawaban Pertanyaan Refleksi

## 1. Mengapa fungsi power() harus dipanggil di dalam term(), bukan sebaliknya?

Karena operator pangkat (^) memiliki prioritas lebih tinggi dibanding operator perkalian (*) dan pembagian (/). Dengan memanggil power() di dalam term(), maka operasi pangkat diproses terlebih dahulu sesuai aturan operator precedence.

## 2. Apa yang terjadi jika variabel z digunakan tetapi tidak ada di symbol_table?

Compiler akan menghasilkan Semantic Error karena variabel z belum didefinisikan di dalam symbol_table pada fase analisis semantik.

## 3. Mengapa instruksi a ^ 2 harus muncul sebelum + pada TAC?

Karena operasi pangkat memiliki prioritas lebih tinggi dibanding penjumlahan. TAC mengikuti urutan evaluasi operator sehingga a ^ 2 dihitung terlebih dahulu sebelum operasi + dijalankan.
