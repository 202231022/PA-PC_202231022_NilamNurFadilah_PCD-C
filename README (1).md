
## Authors

- 202231022-Nilam Nurfadilah 
UAS PCD (Pengolahan Citra Digital - C)


## Filtering Citra
Proses Filtering pada Citra Digital:
Preprocessing:
Sebelum proses filtering dimulai, gambar digital sering kali mengalami tahap preprocessing untuk menghilangkan noise atau mempersiapkan data lainnya.

Jenis Filtering:

Spatial Filtering: Proses di mana setiap piksel dalam gambar diproses secara independen, berdasarkan nilai piksel di sekitarnya. Teknik ini termasuk dalam kategori seperti smoothing (penghalusan), sharpening (pemertajaman), dan edge detection (deteksi tepi).

Frequency Domain Filtering: Mengubah citra ke domain frekuensi (seperti dengan transformasi Fourier) untuk memanipulasi informasi frekuensi gambar, seperti untuk menghilangkan frekuensi tinggi (noise) atau menyoroti frekuensi tertentu.

Filtering Techniques:

Smoothing Filters: Digunakan untuk mengurangi noise atau mengaburkan gambar. Contohnya adalah filter rata-rata (mean filter) dan Gaussian filter.

Sharpening Filters: Meningkatkan detail dan ketajaman gambar. Contoh termasuk filter laplacian dan high-pass filter.

Edge Detection Filters: Mengidentifikasi dan meningkatkan tepi objek dalam gambar, seperti filter Sobel dan Prewitt.

Implementasi Digital:

Algoritma dan Implementasi: Filtering sering diimplementasikan dalam bentuk algoritma komputasi untuk memproses setiap piksel dalam citra berdasarkan jenis filter yang digunakan.

Tool dan Software: Berbagai perangkat lunak seperti Adobe Photoshop, GIMP, atau bahkan bahasa pemrograman seperti Python dengan library seperti OpenCV digunakan untuk menerapkan filter dengan berbagai teknik dan parameter.

Efek dan Aplikasi:

Peningkatan Kualitas Gambar: Filtering digunakan untuk menghasilkan gambar yang lebih tajam, jernih, dan bebas noise.

Analisis dan Deteksi: Filter tepi dapat membantu dalam aplikasi pengolahan citra medis, visi komputer, dan analisis data visual lainnya.

Pertimbangan Penggunaan:

Trade-off: Setiap jenis filter memiliki trade-off antara kejernihan detail dan kehilangan informasi. Pengguna harus mempertimbangkan jenis gambar dan tujuan akhir sebelum memilih teknik filtering yang tepat.