# Week 04 — Reverse Engineering Tools

---

# Ringkasan

Pada pertemuan keempat, saya mempelajari berbagai tools yang umum digunakan dalam Reverse Engineering. Tools ini memiliki peran penting dalam membantu proses analisis binary, baik melalui pendekatan static analysis maupun dynamic analysis.

Materi minggu ini berfokus pada fungsi masing-masing tools, kapan tools tersebut digunakan, serta bagaimana tools tersebut saling melengkapi dalam proses analisis. Dari pembelajaran ini saya mulai memahami bahwa setiap tools memiliki spesialisasi yang berbeda, sehingga pemilihan tools yang tepat sangat memengaruhi efektivitas analisis.

---

# Pembahasan Materi

## 1. Pentingnya Tools dalam Reverse Engineering

Dalam Reverse Engineering, tools menjadi komponen utama untuk membantu proses analisis executable. Tanpa tools yang tepat, proses memahami struktur binary maupun perilaku program akan menjadi sangat sulit.

Secara umum, tools Reverse Engineering digunakan untuk:

* Melihat struktur binary
* Membaca assembly code
* Melakukan debugging
* Monitoring aktivitas sistem
* Menganalisis network traffic

Setiap tools dirancang untuk kebutuhan analisis yang berbeda.

---

## 2. Tools untuk Static Analysis

Static analysis berfokus pada analisis file tanpa menjalankannya. Oleh karena itu, tools yang digunakan biasanya bertujuan untuk membaca struktur internal binary.

Beberapa tools yang umum digunakan antara lain:

| Tools    | Fungsi                    |
| -------- | ------------------------- |
| IDA Free | Disassembler              |
| Ghidra   | Disassembler & Decompiler |
| PE-bear  | Analisis PE Structure     |
| HxD      | Hex Editor                |

Tools ini membantu analyst memahami struktur binary secara lebih detail.

---

## 3. IDA Free

IDA Free merupakan salah satu tools Reverse Engineering yang paling populer.

Fungsi utama IDA Free adalah:

* Disassembly binary
* Function analysis
* Graph view
* Cross reference analysis

IDA Free membantu mengubah machine code menjadi assembly code yang lebih mudah dibaca dan dianalisis.

Saya mulai memahami bahwa tools ini sangat berguna untuk menganalisis alur program dan menemukan fungsi-fungsi penting dalam executable.

---

## 4. Ghidra

Ghidra adalah tools Reverse Engineering yang dikembangkan oleh NSA dan tersedia secara gratis.

Beberapa fitur utama Ghidra:

* Disassembler
* Decompiler
* Function analysis
* Code navigation
* Cross reference

Kelebihan utama Ghidra adalah kemampuan decompiler yang membantu menerjemahkan assembly code menjadi pseudo-code yang lebih mudah dipahami.

---

## 5. Tools untuk Dynamic Analysis

Untuk dynamic analysis, tools yang digunakan berfokus pada monitoring perilaku program ketika dijalankan.

Beberapa tools yang dipelajari antara lain:

| Tools           | Fungsi                     |
| --------------- | -------------------------- |
| x64dbg          | Debugging                  |
| Wireshark       | Network Monitoring         |
| Process Monitor | Monitoring System Activity |
| VirtualBox      | Sandbox Environment        |

Tools ini digunakan untuk mengamati aktivitas runtime sebuah program.

---

## 6. Workflow Penggunaan Tools

Dalam praktiknya, tools Reverse Engineering biasanya digunakan secara berurutan sesuai kebutuhan analisis.

```text id="wk4a11"
Binary File
    │
    ▼
Static Analysis
    │
    ▼
Disassembly
    │
    ▼
Dynamic Analysis
    │
    ▼
Behavior Analysis
```

Workflow ini membantu analyst memperoleh pemahaman menyeluruh mengenai struktur dan perilaku program.

---

# Insight Minggu Ini

Dari materi minggu ini, saya memahami bahwa tools memiliki peran yang sangat penting dalam Reverse Engineering. Setiap tools dirancang untuk tujuan tertentu, sehingga analyst harus memahami kapan dan bagaimana tools tersebut digunakan.

Saya juga mulai memahami bahwa tidak ada satu tools yang dapat menyelesaikan seluruh proses analisis. Biasanya dibutuhkan kombinasi beberapa tools untuk mendapatkan hasil analisis yang lebih lengkap.

---

# Tools yang Dipelajari

* IDA Free
* Ghidra
* PE-bear
* HxD
* x64dbg
* Wireshark

---

# Refleksi Pembelajaran

## Apa yang Saya Pahami

Setelah mempelajari materi minggu ini, saya memahami bahwa setiap tools dalam Reverse Engineering memiliki fungsi yang berbeda sesuai kebutuhan analisis. Tools untuk static analysis membantu membaca struktur binary, sedangkan tools untuk dynamic analysis membantu mengamati perilaku program saat dijalankan.

Saya juga mulai memahami bahwa penggunaan tools yang tepat sangat membantu mempercepat proses analisis.

## Apa yang Masih Membingungkan

Saya masih ingin memahami penggunaan tools seperti Ghidra dan x64dbg secara lebih mendalam, terutama untuk membaca assembly code dan melakukan debugging pada executable yang kompleks.

## Kesimpulan Pribadi

Materi minggu keempat memberikan pemahaman yang lebih jelas mengenai tools yang digunakan dalam Reverse Engineering. Dengan memahami fungsi dasar setiap tools, saya memiliki bekal yang lebih baik untuk mulai melakukan analisis executable secara langsung.

---

