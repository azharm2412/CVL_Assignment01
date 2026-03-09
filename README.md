# Implementasi Image Enhancement pada Berbagai Kondisi Citra

## Deskripsi

Proyek ini mengimplementasikan beberapa metode **Image Enhancement** untuk meningkatkan kualitas visual citra pada berbagai kondisi. Image enhancement bertujuan untuk memperbaiki tampilan citra sehingga informasi di dalamnya menjadi lebih mudah diamati dan dianalisis.

Pada tugas ini, berbagai teknik enhancement diterapkan pada citra dengan kondisi yang berbeda seperti **low contrast, underexposure, overexposure, noise, dan blur**.

Melalui implementasi ini, dilakukan analisis terhadap perubahan citra sebelum dan sesudah proses enhancement baik secara visual maupun melalui distribusi histogram dan statistik piksel.

---

## Kondisi Citra dan Metode Enhancement

Berikut adalah kondisi citra yang dianalisis beserta metode enhancement yang digunakan:

| Kondisi Citra                       | Metode Enhancement |
|-------------------------------------|--------------------|
| Low Contrast                        | Contrast Stretching, Histogram Equalization |
| Underexposure (Citra Gelap)         | Histogram Equalization, Log Transformation |
| Overexposure (Citra Terlalu Terang) | Gamma Correction |
| Blur                                | Laplacian Sharpening |
| Noise                               | Mean Filter, Median Filter, Gaussian Filter |

Seluruh metode diimplementasikan menggunakan **Python dengan library OpenCV, NumPy, dan Matplotlib**.

---

## Alur Implementasi

Secara umum proses yang dilakukan pada setiap eksperimen adalah sebagai berikut:

1. Memuat citra input
2. Mengubah citra menjadi grayscale jika diperlukan
3. Menerapkan metode image enhancement sesuai kondisi citra
4. Menampilkan hasil citra sebelum dan sesudah enhancement
5. Melakukan analisis menggunakan:

   * Perbandingan visual
   * Histogram distribusi intensitas
   * Statistik piksel (mean, standar deviasi, nilai minimum dan maksimum)

Contoh alur proses:

```
Citra Asli
     ↓
Metode Image Enhancement
     ↓
Citra Hasil Enhancement
     ↓
Analisis Histogram dan Statistik Piksel
```

---

## Hasil dan Analisis

Untuk setiap kondisi citra, hasil yang ditampilkan meliputi:

* Citra asli (Original Image)
* Citra setelah enhancement
* Histogram distribusi intensitas
* Statistik piksel (mean, standar deviasi, minimum, maksimum)

Visualisasi ini membantu memahami bagaimana metode enhancement mempengaruhi kualitas citra dan distribusi intensitas piksel.

---


## Kesimpulan

Metode image enhancement dapat meningkatkan kualitas visual citra dan membantu memperjelas informasi yang terdapat pada citra. Namun, setiap metode memiliki karakteristik dan lebih efektif digunakan pada kondisi citra tertentu. Pemilihan metode enhancement yang tepat sangat penting agar hasil peningkatan kualitas citra menjadi optimal.
