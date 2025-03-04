# Hasil Belajar Number & Date Format SQL dari Bootcamp DQLab

Repositori ini berisi kumpulan kode SQL yang saya pelajari selama mengikuti bootcamp DQLab, khususnya mengenai format angka dan tanggal dalam SQL.

## Deskripsi

Dalam repositori ini, Anda akan menemukan berbagai contoh penggunaan fungsi-fungsi SQL untuk memformat angka dan tanggal. Fungsi-fungsi ini sangat penting untuk menyajikan data dalam format yang mudah dibaca dan dipahami.


## Pengenalan Format Angka dan Tanggal

Format angka dan tanggal adalah teknik untuk mengubah tampilan data angka dan tanggal sesuai dengan kebutuhan. Dalam SQL, terdapat berbagai fungsi yang dapat digunakan untuk melakukan format ini.

## Format Angka

### Fungsi-fungsi Format Angka

Beberapa fungsi yang umum digunakan untuk format angka antara lain:

* `FORMAT()`: Memformat angka dengan pemisah ribuan dan desimal.
* `ROUND()`: Membulatkan angka ke jumlah desimal tertentu.

### Contoh Penggunaan Format Angka

```sql
SELECT FORMAT(1234567.89, 2); -- Output: 1,234,567.89
SELECT ROUND(3.14159, 2); -- Output: 3.14
