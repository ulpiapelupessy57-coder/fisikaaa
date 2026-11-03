import React, { useState, useEffect, useRef } from 'react';
import { 
  BookOpen, Clock, CheckCircle2, XCircle, AlertCircle, Award, 
  Printer, LogOut, ChevronRight, ChevronLeft, Flag, Check, 
  HelpCircle, User, FileText, BarChart3, ShieldCheck, Download, 
  Search, Lock, RotateCcw, Eye, Sparkles, Layers, Sliders, ArrowRight,
  TrendingUp, Users, Target, FileSpreadsheet
} from 'lucide-react';

// --- DATA SOAL ASESMEN (40 SOAL LENGKAP) ---
const QUESTION_BANK = [
  // ==================== TOPIC 1: BESARAN DAN SATUAN (1-10) ====================
  {
    id: 1,
    topic: "Besaran dan Satuan",
    question: "Di antara kelompok besaran berikut, yang seluruhnya merupakan besaran pokok dalam Sistem Internasional (SI) adalah...",
    options: [
      "A. Panjang, massa, waktu, dan kecepatan",
      "B. Waktu, suhu, kuat arus listrik, dan intensitas cahaya",
      "C. Massa, gaya, percepatan, dan jumlah zat",
      "D. Panjang, luas, volume, dan massa jenis",
      "E. Suhu, energi, daya, dan tegangan listrik"
    ],
    correctAnswer: 1, // B
    explanation: "Tujuh besaran pokok SI yaitu: Panjang (meter), Massa (kg), Waktu (sekon), Suhu (Kelvin), Kuat Arus Listrik (Ampere), Intensitas Cahaya (kandela), dan Jumlah Zat (mol). Kecepatan, gaya, luas, volume, dan energi adalah besaran turunan."
  },
  {
    id: 2,
    topic: "Besaran dan Satuan",
    question: "Satuan Sistem Internasional (SI) untuk besaran suhu termodinamika dan kuat arus listrik secara berurutan adalah...",
    options: [
      "A. Celcius dan Volt",
      "B. Fahrenheit dan Ohm",
      "C. Kelvin dan Ampere",
      "D. Reamur dan Watt",
      "E. Joule dan Coulumb"
    ],
    correctAnswer: 2, // C
    explanation: "Dalam SI, satuan standar untuk suhu termodinamika adalah Kelvin (K) dan untuk kuat arus listrik adalah Ampere (A)."
  },
  {
    id: 3,
    topic: "Besaran dan Satuan",
    question: "Kelompok besaran di bawah ini yang semuanya merupakan besaran turunan adalah...",
    options: [
      "A. Usaha, daya, massa jenis, dan kecepatan",
      "B. Panjang, kuat arus, gaya, dan waktu",
      "C. Suhu, jumlah zat, volume, dan energi",
      "D. Massa, percepatan, momentum, dan luas",
      "E. Intensitas cahaya, tegangan, daya, dan panjang"
    ],
    correctAnswer: 0, // A
    explanation: "Usaha (Joule), Daya (Watt), Massa Jenis (kg/m³), dan Kecepatan (m/s) seluruhnya diturunkan dari besaran pokok."
  },
  {
    id: 4,
    topic: "Besaran dan Satuan",
    question: "Sebuah bodi motor di Tehoru melaju dengan kecepatan 72 km/jam. Jika kecepatan tersebut dikonversikan ke dalam satuan SI (m/s), nilainya adalah...",
    options: [
      "A. 10 m/s",
      "B. 15 m/s",
      "C. 20 m/s",
      "D. 25 m/s",
      "E. 30 m/s"
    ],
    correctAnswer: 2, // C
    explanation: "Konversi km/jam ke m/s:\n72 km/jam = (72 × 1.000 m) / (3.600 s) = 72.000 / 3.600 = 20 m/s."
  },
  {
    id: 5,
    topic: "Besaran dan Satuan",
    question: "Massa jenis air murni adalah 1 gram/cm³. Dalam satuan Sistem Internasional (SI), nilai massa jenis air tersebut setara dengan...",
    options: [
      "A. 10 kg/m³",
      "B. 100 kg/m³",
      "C. 1.000 kg/m³",
      "D. 10.000 kg/m³",
      "E. 0,001 kg/m³"
    ],
    correctAnswer: 2, // C
    explanation: "1 g/cm³ = (10⁻³ kg) / (10⁻⁶ m³) = 10³ kg/m³ = 1.000 kg/m³."
  },
  {
    id: 6,
    topic: "Besaran dan Satuan",
    question: "Besaran berikut yang tergolong sebagai besaran skalar adalah...",
    options: [
      "A. Perpindahan, kecepatan, dan gaya",
      "B. Massa, waktu, energi, dan suhu",
      "C. Percepatan, momentum, dan impuls",
      "D. Gaya, berat, dan medan listrik",
      "E. Kecepatan, massa jenis, dan torsi"
    ],
    correctAnswer: 1, // B
    explanation: "Besaran skalar hanya memiliki nilai/besaran tanpa memiliki arah. Massa, waktu, energi, dan suhu adalah besaran skalar. Besaran seperti gaya, kecepatan, dan percepatan memiliki arah (vektor)."
  },
  {
    id: 7,
    topic: "Besaran dan Satuan",
    question: "Satuan dari besaran daya dalam SI adalah Watt. Satuan Watt ini jika diuraikan ke dalam satuan besaran pokok adalah...",
    options: [
      "A. kg·m/s²",
      "B. kg·m²/s²",
      "C. kg·m²/s³",
      "D. kg·m/s³",
      "E. kg·m²/s"
    ],
    correctAnswer: 2, // C
    explanation: "Daya (P) = Usaha (W) / Waktu (t) = (Gaya × Jarak) / Waktu = (kg·m/s² × m) / s = kg·m²/s³."
  },
  {
    id: 8,
    topic: "Besaran dan Satuan",
    question: "Manakah pasangan besaran dan satuan SI yang TIDAK TEPAT di bawah ini?",
    options: [
      "A. Tekanan – Pascal (N/m²)",
      "B. Impuls – Newton sekon (N·s)",
      "C. Frekuensi – Hertz (1/s)",
      "D. Muatan Listrik – Ampere (A)",
      "E. Energi Kinetik – Joule (kg·m²/s²)"
    ],
    correctAnswer: 3, // D
    explanation: "Satuan SI untuk muatan listrik adalah Coulomb (C), sedangkan Ampere (A) adalah satuan untuk Kuat Arus Listrik."
  },
  {
    id: 9,
    topic: "Besaran dan Satuan",
    question: "Tekanan hidrostatik rumusnya P = ρ·g·h. Satuan pokok pembentuk besaran tekanan P adalah...",
    options: [
      "A. kg·m⁻¹·s⁻²",
      "B. kg·m·s⁻²",
      "C. kg·m²·s⁻²",
      "D. kg·m⁻²·s⁻¹",
      "E. kg·m⁻³·s⁻²"
    ],
    correctAnswer: 0, // A
    explanation: "P = Gaya / Luas = (kg·m/s²) / m² = kg/(m·s²) = kg·m⁻¹·s⁻²."
  },
  {
    id: 10,
    topic: "Besaran dan Satuan",
    question: "Awalan (prefix) mikro (μ) dan mega (M) dalam satuan SI menyatakan kelipatan berpangkat...",
    options: [
      "A. 10⁻³ dan 10⁶",
      "B. 10⁻⁶ dan 10⁶",
      "C. 10⁻⁹ dan 10⁹",
      "D. 10⁻⁶ dan 10³",
      "E. 10⁻¹² dan 10⁶"
    ],
    correctAnswer: 1, // B
    explanation: "Mikro (μ) merepresentasikan 10⁻⁶ (sepersatu juta) dan Mega (M) merepresentasikan 10⁶ (satu juta)."
  },

  // ==================== TOPIC 2: ANGKA PENTING (11-20) ====================
  {
    id: 11,
    topic: "Angka Penting",
    question: "Banyaknya angka penting pada hasil pengukuran 0,005070 meter adalah...",
    options: [
      "A. 3 angka penting",
      "B. 4 angka penting",
      "C. 5 angka penting",
      "D. 6 angka penting",
      "E. 7 angka penting"
    ],
    correctAnswer: 1, // B
    explanation: "Angka nol di sebelah kiri angka bukan nol pertama (0,00) bukan AP. Angka 5, 0 (di antara angka bukan nol), 7, dan 0 (di sebelah kanan desimal setelah angka bukan nol) adalah AP. Jadi ada 4 AP: 5, 0, 7, 0."
  },
  {
    id: 12,
    topic: "Angka Penting",
    question: "Hasil penjumlahan dari 12,54 gram + 5,3 gram menurut aturan penulisan angka penting adalah...",
    options: [
      "A. 17,84 gram",
      "B. 17,8 gram",
      "C. 17,9 gram",
      "D. 18,0 gram",
      "E. 17,840 gram"
    ],
    correctAnswer: 1, // B
    explanation: "12,54 memiliki 2 angka di belakang koma (taksiran pada 4).\n5,3 memiliki 1 angka di belakang koma (taksiran pada 3).\nHasil penjumlahan: 17,84 gram harus dibulatkan menjadi 1 angka di belakang koma, yaitu 17,8 gram."
  },
  {
    id: 13,
    topic: "Angka Penting",
    question: "Sebuah bidang berbentuk persegi panjang memiliki panjang 4,25 cm dan lebar 2,1 cm. Luas bidang tersebut menurut aturan angka penting adalah...",
    options: [
      "A. 8,925 cm²",
      "B. 8,93 cm²",
      "C. 8,9 cm²",
      "D. 9,0 cm²",
      "E. 8,92 cm²"
    ],
    correctAnswer: 2, // C
    explanation: "Panjang 4,25 cm (3 AP) × Lebar 2,1 cm (2 AP).\nHasil perkalian: 4,25 × 2,1 = 8,925 cm².\nHasil perkalian mengikuti AP paling sedikit (2 AP), sehingga dibulatkan menjadi 8,9 cm²."
  },
  {
    id: 14,
    topic: "Angka Penting",
    question: "Penulisan notasi ilmiah untuk bilangan 0,0000000456 meter yang benar adalah...",
    options: [
      "A. 45,6 × 10⁻⁹ m",
      "B. 4,56 × 10⁻⁸ m",
      "C. 4,56 × 10⁻⁷ m",
      "D. 0,456 × 10⁻⁷ m",
      "E. 4,56 × 10⁸ m"
    ],
    correctAnswer: 1, // B
    explanation: "Notasi ilmiah ditulis a × 10ⁿ di mana 1 ≤ a < 10. Menggeser koma 8 tempat ke kanan memberikan 4,56 × 10⁻⁸ m."
  },
  {
    id: 15,
    topic: "Angka Penting",
    question: "Massa 5 buah benda yang identik masing-masing adalah 2,45 gram. Jumlah massa total kelima benda tersebut sesuai aturan penulisan angka penting adalah...",
    options: [
      "A. 12,25 gram",
      "B. 12,3 gram",
      "C. 12,2 gram",
      "D. 12 gram",
      "E. 12,250 gram"
    ],
    correctAnswer: 0, // A
    explanation: "Perkalian antara hasil pengukuran (2,45 gram -> 3 AP) dengan angka eksak (5 buah) menghasilkan angka penting sejumlah angka penting pada hasil pengukuran (3 AP). 2,45 × 5 = 12,25 gram (4 angka, tetapi memiliki 3 AP dalam konteks ini atau dibulatkan sesuai ketelitian alat)."
  },
  {
    id: 16,
    topic: "Angka Penting",
    question: "Hasil pengurangan dari 25,745 cm – 1,2 cm berdasarkan aturan angka penting adalah...",
    options: [
      "A. 24,545 cm",
      "B. 24,55 cm",
      "C. 24,5 cm",
      "D. 24,6 cm",
      "E. 25,0 cm"
    ],
    correctAnswer: 2, // C
    explanation: "25,745 (3 desimal) – 1,2 (1 desimal) = 24,545 cm. Hasilnya dibulatkan menjadi 1 angka di belakang koma yaitu 24,5 cm."
  },
  {
    id: 17,
    topic: "Angka Penting",
    question: "Panjang sisi sebuah kubus adalah 2,0 cm. Volume kubus tersebut menurut aturan angka penting adalah...",
    options: [
      "A. 8 cm³",
      "B. 8,0 cm³",
      "C. 8,00 cm³",
      "D. 8,000 cm³",
      "E. 8,1 cm³"
    ],
    correctAnswer: 1, // B
    explanation: "Sisi = 2,0 cm (2 AP). Volume = s³ = (2,0)³ = 8,000... cm³. Karena input memiliki 2 AP, maka volume harus ditulis 8,0 cm³ (2 AP)."
  },
  {
    id: 18,
    topic: "Angka Penting",
    question: "Manakah di antara bilangan-bilangan berikut yang memiliki TEPAT 3 angka penting?",
    options: [
      "A. 0,003",
      "B. 0,030",
      "C. 0,300",
      "D. 300,0",
      "E. 0,03030"
    ],
    correctAnswer: 2, // C
    explanation: "A = 1 AP (3), B = 2 AP (3,0), C = 3 AP (3, 0, 0), D = 4 AP (3,0,0,0), E = 4 AP (3,0,3,0)."
  },
  {
    id: 19,
    topic: "Angka Penting",
    question: "Akar kuadrat dari bilangan 1,44 menurut aturan angka penting adalah...",
    options: [
      "A. 1,2",
      "B. 1,20",
      "C. 1,200",
      "D. 1,2000",
      "E. 1"
    ],
    correctAnswer: 1, // B
    explanation: "1,44 memiliki 3 angka penting. Maka hasil penarik akar √1,44 = 1,2 harus disesuaikan menjadi 3 AP yaitu 1,20."
  },
  {
    id: 20,
    topic: "Angka Penting",
    question: "Pernyataan berikut mengenai angka penting yang BENAR adalah...",
    options: [
      "A. Semua angka nol adalah angka penting",
      "B. Angka nol di antara angka bukan nol bukan merupakan angka penting",
      "C. Angka nol di sebelah kiri angka bukan nol pertama tidak termasuk angka penting",
      "D. Hasil pembagian angka penting selalu memiliki 5 angka penting",
      "E. Angka eksak diperoleh dari hasil pengukuran menggunakan alat ukur"
    ],
    correctAnswer: 2, // C
    explanation: "Angka nol yang terletak di sebelah kiri angka bukan nol pertama (misal 0,002) berfungsi hanya sebagai penunjuk tempat koma desimal dan BUKAN angka penting."
  },

  // ==================== TOPIC 3: PENGUKURAN (21-30) ====================
  {
    id: 21,
    topic: "Pengukuran",
    visualType: "vernier_caliper",
    visualData: { main: "2.3", nonius: "7" },
    question: "Perhatikan gambar hasil pengukuran diameter pipa menggunakan Jangka Sorong berikut! Nilai pembacaan jangka sorong tersebut adalah...",
    options: [
      "A. 2,37 cm",
      "B. 2,47 cm",
      "C. 2,30 cm",
      "D. 3,07 cm",
      "E. 2,73 cm"
    ],
    correctAnswer: 0, // A
    explanation: "Skala Utama (SU) = 2,3 cm (garis sebelum nol nonius).\nSkala Nonius (SN) = 7 × 0,01 cm = 0,07 cm.\nHasil Pengukuran = SU + SN = 2,3 cm + 0,07 cm = 2,37 cm."
  },
  {
    id: 22,
    topic: "Pengukuran",
    visualType: "micrometer_screw",
    visualData: { main: "4.5", nonius: "38" },
    question: "Hasil pengukuran ketebalan koin rupiah dengan Mikrometer Sekrup ditunjukkan pada diagram di bawah ini. Tebal koin tersebut adalah...",
    options: [
      "A. 4,38 mm",
      "B. 4,50 mm",
      "C. 4,88 mm",
      "D. 4,78 mm",
      "E. 5,38 mm"
    ],
    correctAnswer: 2, // C
    explanation: "Skala Utama (SU) = 4,5 mm.\nSkala Nonius (SN) = 38 × 0,01 mm = 0,38 mm.\nHasil = SU + SN = 4,5 mm + 0,38 mm = 4,88 mm."
  },
  {
    id: 23,
    topic: "Pengukuran",
    question: "Batas ketelitian (Nilai Skala Terkecil/NST) dari mistar plastik biasa, jangka sorong baku, dan mikrometer sekrup berturut-turut adalah...",
    options: [
      "A. 1 mm; 0,1 mm; 0,01 mm",
      "B. 0,1 mm; 0,01 mm; 0,001 mm",
      "C. 1 cm; 0,1 cm; 0,01 cm",
      "D. 0,5 mm; 0,05 mm; 0,005 mm",
      "E. 1 mm; 0,01 mm; 0,001 mm"
    ],
    correctAnswer: 0, // A
    explanation: "Mistar memilki NST 1 mm (0,1 cm), Jangka Sorong standar 0,1 mm (0,01 cm), dan Mikrometer Sekrup 0,01 mm (0,001 cm)."
  },
  {
    id: 24,
    topic: "Pengukuran",
    question: "Ketidakpastian mutlak (Δx) pada pengukuran tunggal menggunakan alat ukur dirumuskan sebagai...",
    options: [
      "A. Δx = Nilai Skala Terkecil (NST)",
      "B. Δx = ½ × Nilai Skala Terkecil (NST)",
      "C. Δx = 2 × Nilai Skala Terkecil (NST)",
      "D. Δx = ⅓ × Nilai Skala Terkecil (NST)",
      "E. Δx = ⅕ × Nilai Skala Terkecil (NST)"
    ],
    correctAnswer: 1, // B
    explanation: "Pada pengukuran tunggal, ketidakpastian mutlak dilaporkan sebesar setengah dari nilai skala terkecil alat ukur (Δx = ½ × NST)."
  },
  {
    id: 25,
    topic: "Pengukuran",
    question: "Seorang siswa mengukur panjang papan tulis dengan mistar yang memiliki skala terkecil 1 mm. Hasil pengukuran dituliskan (50,0 ± Δx) cm. Nilai Δx yang tepat adalah...",
    options: [
      "A. 0,1 cm",
      "B. 0,05 cm",
      "C. 0,5 cm",
      "D. 0,01 cm",
      "E. 1 cm"
    ],
    correctAnswer: 1, // B
    explanation: "NST mistar = 1 mm = 0,1 cm. Ketidakpastian Δx = ½ × NST = ½ × 0,1 cm = 0,05 cm."
  },
  {
    id: 26,
    topic: "Pengukuran",
    visualType: "triple_beam",
    visualData: { b1: "200", b2: "40", b3: "5.6" },
    question: "Perhatikan posisi anting pada neraca Ohauss tiga lengan saat menimbang sampel kerikil Tehoru berikut. Massa sampel tersebut adalah...",
    options: [
      "A. 245,6 gram",
      "B. 254,6 gram",
      "C. 204,56 gram",
      "D. 240,56 gram",
      "E. 425,6 gram"
    ],
    correctAnswer: 0, // A
    explanation: "Massa total = Lengan Ratusan + Lengan Puluhan + Lengan Satuan = 200 g + 40 g + 5,6 g = 245,6 gram."
  },
  {
    id: 27,
    topic: "Pengukuran",
    question: "Kesalahan sistematis dalam pengukuran dapat disebabkan oleh...",
    options: [
      "A. Fluktuasi tegangan listrik mendadak",
      "B. Landasan tempat alat yang bergetar",
      "C. Kalibrasi alat ukur yang tidak tepat atau titik nol yang bergeser",
      "D. Perubahan suhu lingkungan secara acak",
      "E. Gerak brown molekul udara"
    ],
    correctAnswer: 2, // C
    explanation: "Kesalahan kalibrasi, paralaks berulang, dan pergeseran titik nol adalah contoh kesalahan sistematis yang dapat diatasi dengan kalibrasi ulang alat."
  },
  {
    id: 28,
    topic: "Pengukuran",
    question: "Pengukuran berulang massa benda sebanyak 5 kali menghasilkan rata-rata x̄ = 10,0 g dan simpangan baku sₓ = 0,1 g. Ketidakpastian relatif pengukuran tersebut adalah...",
    options: [
      "A. 0,1%",
      "B. 1,0%",
      "C. 10%",
      "D. 0,01%",
      "E. 5,0%"
    ],
    correctAnswer: 1, // B
    explanation: "Ketidakpastian Relatif = (Δx / x̄) × 100% = (0,1 / 10,0) × 100% = 1,0%."
  },
  {
    id: 29,
    topic: "Pengukuran",
    question: "Alat ukur yang paling presisi dan cocok untuk mengukur diameter luar kawat tembaga yang sangat tipis adalah...",
    options: [
      "A. Metran gulung (rol meter)",
      "B. Mistar kayu",
      "C. Jangka sorong",
      "D. Mikrometer sekrup",
      "E. Meteran pita"
    ],
    correctAnswer: 3, // D
    explanation: "Mikrometer sekrup memiliki tingkat ketelitian paling tinggi (0,01 mm) dibanding alat ukur panjang lainnya, sangat cocok untuk kawat tipis atau lembaran kertas."
  },
  {
    id: 30,
    topic: "Pengukuran",
    question: "Posisi mata pengamat yang tidak tegak lurus terhadap skala alat ukur saat membaca hasil pengukuran akan menyebabkan kesalahan...",
    options: [
      "A. Kesalahan acak",
      "B. Kesalahan paralaks",
      "C. Kesalahan zerofix",
      "D. Kesalahan kalkulasi",
      "E. Kesalahan teknis"
    ],
    correctAnswer: 1, // B
    explanation: "Kesalahan membaca skala akibat sudut pandang mata tidak tegak lurus garis skala dinamakan kesalahan paralaks."
  },

  // ==================== TOPIC 4: DIMENSI BESARAN (31-40) ====================
  {
    id: 31,
    topic: "Dimensi Besaran",
    question: "Dimensi dari besaran Kecepatan (v) dan Percepatan (a) secara berurutan adalah...",
    options: [
      "A. [L][T]⁻¹ dan [L][T]⁻²",
      "B. [L][T] dan [L][T]²",
      "C. [M][L][T]⁻¹ dan [M][L][T]⁻²",
      "D. [L]²[T]⁻¹ dan [L]²[T]⁻²",
      "E. [M][T]⁻¹ dan [M][T]⁻²"
    ],
    correctAnswer: 0, // A
    explanation: "Kecepatan (v = m/s) -> [L][T]⁻¹.\nPercepatan (a = m/s²) -> [L][T]⁻²."
  },
  {
    id: 32,
    topic: "Dimensi Besaran",
    question: "Dimensi [M][L][T]⁻² menyatakan dimensi dari besaran...",
    options: [
      "A. Usaha",
      "B. Tekanan",
      "C. Gaya",
      "D. Daya",
      "E. Momentum"
    ],
    correctAnswer: 2, // C
    explanation: "Gaya (F = m × a) = kg × m/s² -> [M] × [L] × [T]⁻² = [M][L][T]⁻²."
  },
  {
    id: 33,
    topic: "Dimensi Besaran",
    question: "Besaran Usaha (W) dan Energi Kinetik (EK) memiliki dimensi yang sama yaitu...",
    options: [
      "A. [M][L][T]⁻¹",
      "B. [M][L]²[T]⁻²",
      "C. [M][L]⁻¹[T]⁻²",
      "D. [M][L]²[T]⁻³",
      "E. [M][L]³[T]⁻²"
    ],
    correctAnswer: 1, // B
    explanation: "Usaha = Gaya × Jarak = (kg·m/s²) × m = kg·m²/s² -> [M][L]²[T]⁻².\nEnergi Kinetik = ½ m v² = kg × (m/s)² = kg·m²/s² -> [M][L]²[T]⁻²."
  },
  {
    id: 34,
    topic: "Dimensi Besaran",
    question: "Dimensi dari besaran Daya (Power) adalah...",
    options: [
      "A. [M][L]²[T]⁻²",
      "B. [M][L]²[T]⁻³",
      "C. [M][L][T]⁻³",
      "D. [M][L]⁻¹[T]⁻²",
      "E. [M][L]²[T]⁻¹"
    ],
    correctAnswer: 1, // B
    explanation: "Daya = Usaha / Waktu = [M][L]²[T]⁻² / [T] = [M][L]²[T]⁻³."
  },
  {
    id: 35,
    topic: "Dimensi Besaran",
    question: "Dimensi dari besaran Tekanan (P = F / A) adalah...",
    options: [
      "A. [M][L]⁻¹[T]⁻²",
      "B. [M][L][T]⁻²",
      "C. [M][L]⁻²[T]⁻²",
      "D. [M][L]²[T]⁻²",
      "E. [M][L]⁻¹[T]⁻¹"
    ],
    correctAnswer: 0, // A
    explanation: "Tekanan = Gaya / Luas = [M][L][T]⁻² / [L]² = [M][L]⁻¹[T]⁻²."
  },
  {
    id: 36,
    topic: "Dimensi Besaran",
    question: "Massa jenis (ρ) didefinisikan sebagai massa per satuan volume. Dimensi dari massa jenis adalah...",
    options: [
      "A. [M][L]⁻²",
      "B. [M][L]⁻³",
      "C. [M][L]³",
      "D. [M][L]⁻¹[T]",
      "E. [M][L]⁻³[T]⁻¹"
    ],
    correctAnswer: 1, // B
    explanation: "Massa Jenis (ρ) = Massa / Volume = [M] / [L]³ = [M][L]⁻³."
  },
  {
    id: 37,
    topic: "Dimensi Besaran",
    question: "Momentum p didefinisikan p = m·v. Dimensi dari besaran momentum adalah...",
    options: [
      "A. [M][L][T]⁻¹",
      "B. [M][L][T]⁻²",
      "C. [M][L]²[T]⁻¹",
      "D. [M][L]⁻¹[T]⁻¹",
      "E. [M][L]²[T]⁻²"
    ],
    correctAnswer: 0, // A
    explanation: "Momentum = Massa × Kecepatan = [M] × [L][T]⁻¹ = [M][L][T]⁻¹."
  },
  {
    id: 38,
    topic: "Dimensi Besaran",
    question: "Dalam persamaan s = v₀·t + ½ a·t², dimensi dari suku (v₀·t) dan suku (½ a·t²) keduanya adalah...",
    options: [
      "A. [L][T]",
      "B. [L]",
      "C. [L][T]⁻¹",
      "D. [L]²",
      "E. [T]"
    ],
    correctAnswer: 1, // B
    explanation: "v₀·t = ([L][T]⁻¹) × [T] = [L].\n½ a·t² = ([L][T]⁻²) × [T]² = [L].\nKedua suku memiliki dimensi Panjang [L], sehingga persamaan tersebut konsisten secara dimensi."
  },
  {
    id: 39,
    topic: "Dimensi Besaran",
    question: "Konstanta gravitasi umum (G) dalam hukum Newton F = G·(m₁·m₂)/r² memiliki dimensi...",
    options: [
      "A. [M]⁻¹[L]³[T]⁻²",
      "B. [M][L]³[T]⁻²",
      "C. [M]⁻¹[L]²[T]⁻²",
      "D. [M]⁻²[L]³[T]⁻¹",
      "E. [M][L]²[T]⁻²"
    ],
    correctAnswer: 0, // A
    explanation: "G = (F × r²) / (m₁ × m₂) = ([M][L][T]⁻² × [L]²) / ([M]²) = [M]⁻¹[L]³[T]⁻²."
  },
  {
    id: 40,
    topic: "Dimensi Besaran",
    question: "Dua besaran fisika berikut yang memiliki DIMENSI SAMA adalah...",
    options: [
      "A. Gaya dan Usaha",
      "B. Kecepatan dan Percepatan",
      "C. Energi Potensial dan Impuls",
      "D. Usaha dan Momen Gaya (Torsi)",
      "E. Tekanan dan Daya"
    ],
    correctAnswer: 3, // D
    explanation: "Usaha = Gaya × Jarak = [M][L]²[T]⁻².\nMomen Gaya (Torsi) = Gaya × Lengan Momen = [M][L]²[T]⁻².\nKeduanya memiliki dimensi yang persis sama!"
  }
];

// --- MAIN APP COMPONENT ---
export default function App() {
  // Navigation & State Management
  const [currentScreen, setCurrentScreen] = useState('welcome'); // welcome, register, exam, result, review, dashboard
  const [studentInfo, setStudentInfo] = useState({ name: '', class: 'X-1', rollNo: '' });
  const [currentQuestionIndex, setCurrentQuestionIndex] = useState(0);
  const [userAnswers, setUserAnswers] = useState({}); // { questionId: optionIndex }
  const [flaggedQuestions, setFlaggedQuestions] = useState({}); // { questionId: true }
  
  // Timer State (60 Minutes = 3600 Seconds)
  const EXAM_DURATION = 3600;
  const [timeLeft, setTimeLeft] = useState(EXAM_DURATION);
  const [isTimerRunning, setIsTimerRunning] = useState(false);
  const [examSubmitted, setExamSubmitted] = useState(false);

  // Teacher Dashboard Auth State
  const [isTeacherLoggedIn, setIsTeacherLoggedIn] = useState(false);
  const [teacherPinInput, setTeacherPinInput] = useState('');
  const [pinError, setPinError] = useState('');
  const [showPinModal, setShowPinModal] = useState(false);

  // Storage Key Constant
  const STORAGE_KEY = 'PHYSICS_ASSESSMENT_STORE_V1';
  const TIMER_STORAGE_KEY = 'PHYSICS_ASSESSMENT_TIMER';

  // State for all submitted exam records
  const [savedRecords, setSavedRecords] = useState([]);

  // Modals
  const [showQuestionGrid, setShowQuestionGrid] = useState(false);
  const [showSubmitModal, setShowSubmitModal] = useState(false);
  const [showInfoModal, setShowInfoModal] = useState(false);

  // Search & Filter for Dashboard
  const [searchQuery, setSearchQuery] = useState('');
  const [classFilter, setClassFilter] = useState('ALL');

  // Load Saved Records & Timer on Initialization
  useEffect(() => {
    try {
      const storedData = localStorage.getItem(STORAGE_KEY);
      if (storedData) {
        setSavedRecords(JSON.parse(storedData));
      }
    } catch (err) {
      console.error("Error reading storage:", err);
    }
  }, []);

  // Timer Effect
  useEffect(() => {
    let timer = null;
    if (isTimerRunning && timeLeft > 0) {
      timer = setInterval(() => {
        setTimeLeft((prev) => {
          const updated = prev - 1;
          localStorage.setItem(TIMER_STORAGE_KEY, updated.toString());
          if (updated <= 0) {
            clearInterval(timer);
            handleAutoSubmit();
            return 0;
          }
          return updated;
        });
      }, 1000);
    }
    return () => clearInterval(timer);
  }, [isTimerRunning, timeLeft]);

  // Formatter for MM:SS
  const formatTime = (seconds) => {
    const mins = Math.floor(seconds / 60);
    const secs = seconds % 60;
    return `${mins.toString().padStart(2, '0')}:${secs.toString().padStart(2, '0')}`;
  };

  // Start Exam Action
  const handleStartExam = (e) => {
    e.preventDefault();
    if (!studentInfo.name.trim() || !studentInfo.rollNo.trim()) {
      alert('Mohon isi nama lengkap dan nomor absen terlebih dahulu!');
      return;
    }

    // Reset Exam State
    setUserAnswers({});
    setFlaggedQuestions({});
    setCurrentQuestionIndex(0);
    setTimeLeft(EXAM_DURATION);
    setIsTimerRunning(true);
    setExamSubmitted(false);
    setCurrentScreen('exam');
  };

  // Select Answer
  const handleSelectOption = (optionIndex) => {
    const qId = QUESTION_BANK[currentQuestionIndex].id;
    setUserAnswers(prev => ({ ...prev, [qId]: optionIndex }));
  };

  // Toggle Flag
  const handleToggleFlag = () => {
    const qId = QUESTION_BANK[currentQuestionIndex].id;
    setFlaggedQuestions(prev => ({ ...prev, [qId]: !prev[qId] }));
  };

  // Auto Submit when timer runs out
  const handleAutoSubmit = () => {
    alert("Waktu pengerjaan telah habis! Sistem akan mengumpulkan jawaban Anda secara otomatis.");
    processSubmit();
  };

  // Process Final Score & Save Record
  const processSubmit = () => {
    setIsTimerRunning(false);
    setExamSubmitted(true);

    // Calculate score
    let correctCount = 0;
    const topicBreakdown = {
      "Besaran dan Satuan": { correct: 0, total: 10 },
      "Angka Penting": { correct: 0, total: 10 },
      "Pengukuran": { correct: 0, total: 10 },
      "Dimensi Besaran": { correct: 0, total: 10 }
    };

    QUESTION_BANK.forEach((q) => {
      const uAns = userAnswers[q.id];
      if (uAns !== undefined && uAns === q.correctAnswer) {
        correctCount += 1;
        if (topicBreakdown[q.topic]) {
          topicBreakdown[q.topic].correct += 1;
        }
      }
    });

    const finalScore = Math.round((correctCount / QUESTION_BANK.length) * 100);

    let predicate = 'Perlu Bimbingan';
    if (finalScore >= 90) predicate = 'Sangat Baik';
    else if (finalScore >= 80) predicate = 'Baik';
    else if (finalScore >= 70) predicate = 'Cukup';

    const durationSpent = EXAM_DURATION - timeLeft;

    const newRecord = {
      id: 'REC-' + Date.now(),
      studentInfo,
      date: new Date().toLocaleString('id-ID'),
      score: finalScore,
      correctCount,
      totalQuestions: QUESTION_BANK.length,
      predicate,
      durationSpent,
      userAnswers,
      topicBreakdown
    };

    // Save to LocalStorage
    const updatedRecords = [newRecord, ...savedRecords];
    setSavedRecords(updatedRecords);
    try {
      localStorage.setItem(STORAGE_KEY, JSON.stringify(updatedRecords));
      localStorage.removeItem(TIMER_STORAGE_KEY);
    } catch (err) {
      console.error("Storage save failed:", err);
    }

    setShowSubmitModal(false);
    setCurrentScreen('result');
  };

  // Teacher Login Handler
  const handleTeacherLogin = (e) => {
    e.preventDefault();
    if (teacherPinInput === '12345' || teacherPinInput === 'guru123') {
      setIsTeacherLoggedIn(true);
      setShowPinModal(false);
      setTeacherPinInput('');
      setPinError('');
      setCurrentScreen('dashboard');
    } else {
      setPinError('PIN atau kata sandi tidak valid. Gunakan 12345');
    }
  };

  // Current Active Record (for Result screen)
  const currentResultRecord = savedRecords.length > 0 ? savedRecords[0] : null;

  // Render Instrument Diagram Helper
  const renderInstrumentVisual = (type, data) => {
    if (type === 'vernier_caliper') {
      return (
        <div className="bg-slate-900 border border-slate-700 rounded-xl p-4 my-4 flex flex-col items-center justify-center">
          <div className="text-xs text-sky-400 font-mono mb-2 flex items-center gap-1">
            <Sliders className="w-4 h-4" /> SIMULASI DIAGRAM JANGKA SORONG (SU: 2,3 cm | SN: 7)
          </div>
          <svg viewBox="0 0 500 120" className="w-full max-w-lg">
            {/* Main Beam */}
            <rect x="20" y="20" width="460" height="40" fill="#334155" stroke="#64748b" strokeWidth="2" rx="4" />
            {/* Main Scale Lines (cm) */}
            {[0, 1, 2, 3, 4].map(cm => (
              <g key={cm}>
                <line x5={50 + cm * 90} y1="20" x2={50 + cm * 90} y2="40" stroke="#f8fafc" strokeWidth="2" />
                <text x={50 + cm * 90} y="15" fill="#94a3b8" fontSize="10" textAnchor="middle" fontWeight="bold">{cm + 2} cm</text>
                {[1,2,3,4,5,6,7,8,9].map(mm => (
                  <line key={mm} x1={50 + cm * 90 + mm * 9} y1="20" x2={50 + cm * 90 + mm * 9} y2={mm === 5 ? 35 : 30} stroke="#cbd5e1" strokeWidth="1" />
                ))}
              </g>
            ))}
            {/* Vernier Scale Slider */}
            <rect x="70" y="45" width="120" height="45" fill="#0284c7" fillOpacity="0.85" stroke="#38bdf8" strokeWidth="2" rx="4" />
            {/* Vernier Scale Marks */}
            {[0,1,2,3,4,5,6,7,8,9,10].map(v => (
              <line key={v} x1={77 + v * 8.1} y1="45" x2={77 + v * 8.1} y2="65" stroke={v === 7 ? "#f97316" : "#ffffff"} strokeWidth={v === 7 ? "2.5" : "1.2"} />
            ))}
            {/* Coincidence Marker Arrow */}
            <path d="M 133.7 75 L 133.7 68 L 130 65 L 137 65 Z" fill="#f97316" />
            <text x="133.7" y="88" fill="#f97316" fontSize="9" textAnchor="middle" fontWeight="bold">Garis Lurus (7)</text>
          </svg>
        </div>
      );
    }

    if (type === 'micrometer_screw') {
      return (
        <div className="bg-slate-900 border border-slate-700 rounded-xl p-4 my-4 flex flex-col items-center justify-center">
          <div className="text-xs text-sky-400 font-mono mb-2 flex items-center gap-1">
            <Sliders className="w-4 h-4" /> SIMULASI MIKROMETER SEKRUP (SU: 4,5 mm | SN: 38)
          </div>
          <svg viewBox="0 0 500 130" className="w-full max-w-lg">
            {/* Main Barrel */}
            <rect x="40" y="30" width="220" height="50" fill="#334155" stroke="#64748b" strokeWidth="2" />
            {/* Main Horizontal Baseline */}
            <line x1="40" y1="55" x2="260" y2="55" stroke="#e2e8f0" strokeWidth="2" />
            {/* Main Scale Marks (mm top, 0.5mm bottom) */}
            {[0,1,2,3,4,5].map(mm => (
              <g key={mm}>
                <line x1={60 + mm * 30} y1="30" x2={60 + mm * 30} y2="55" stroke="#f8fafc" strokeWidth="2" />
                <text x={60 + mm * 30} y="25" fill="#cbd5e1" fontSize="10" textAnchor="middle">{mm}</text>
                {mm < 5 && <line x1={75 + mm * 30} y1="55" x2={75 + mm * 30} y2="70" stroke="#94a3b8" strokeWidth="1.5" />}
              </g>
            ))}
            {/* Thimble / Rotating Sleeve */}
            <path d="M 240 20 L 360 20 L 360 90 L 240 90 Z" fill="#0284c7" fillOpacity="0.85" stroke="#38bdf8" strokeWidth="2" />
            {/* Thimble Lines */}
            {[30, 35, 38, 40, 45].map(val => (
              <g key={val}>
                <line x1="240" y1={55 - (val - 38) * 8} x2="270" y2={55 - (val - 38) * 8} stroke={val === 38 ? "#f97316" : "#ffffff"} strokeWidth={val === 38 ? "2.5" : "1.2"} />
                <text x="275" y={58 - (val - 38) * 8} fill={val === 38 ? "#f97316" : "#ffffff"} fontSize="9" fontWeight={val === 38 ? "bold" : "normal"}>{val}</text>
              </g>
            ))}
            {/* Alignment indicator */}
            <line x1="200" y1="55" x2="240" y2="55" stroke="#f97316" strokeWidth="2" strokeDasharray="3 3" />
          </svg>
        </div>
      );
    }

    if (type === 'triple_beam') {
      return (
        <div className="bg-slate-900 border border-slate-700 rounded-xl p-4 my-4 flex flex-col items-center justify-center">
          <div className="text-xs text-sky-400 font-mono mb-2 flex items-center gap-1">
            <Sliders className="w-4 h-4" /> SKALA NERACA OHAUSS 3 LENGAN (200g + 40g + 5,6g)
          </div>
          <div className="w-full max-w-lg space-y-2">
            <div className="bg-slate-800 p-2 rounded border border-slate-700 flex justify-between items-center text-xs">
              <span className="text-slate-400 font-mono">Lengan 100g (Ratusan):</span>
              <span className="text-sky-400 font-bold font-mono">200 gram</span>
            </div>
            <div className="bg-slate-800 p-2 rounded border border-slate-700 flex justify-between items-center text-xs">
              <span className="text-slate-400 font-mono">Lengan 10g (Puluhan):</span>
              <span className="text-sky-400 font-bold font-mono">40 gram</span>
            </div>
            <div className="bg-slate-800 p-2 rounded border border-slate-700 flex justify-between items-center text-xs">
              <span className="text-slate-400 font-mono">Lengan 1g (Satuan + Desimal):</span>
              <span className="text-amber-400 font-bold font-mono">5,6 gram</span>
            </div>
          </div>
        </div>
      );
    }

    return null;
  };

  return (
    <div className="min-h-screen bg-slate-950 text-slate-100 font-sans antialiased selection:bg-sky-500 selection:text-white">
      {/* GLOBAL HEADER */}
      <header className="no-print sticky top-0 z-40 bg-slate-900/90 backdrop-blur-md border-b border-slate-800 px-4 py-3 shadow-lg">
        <div className="max-w-7xl mx-auto flex items-center justify-between">
          <div 
            onClick={() => setCurrentScreen('welcome')}
            className="flex items-center gap-3 cursor-pointer group"
          >
            <div className="w-10 h-10 rounded-xl bg-gradient-to-tr from-sky-600 to-cyan-400 flex items-center justify-center shadow-lg shadow-sky-500/20 group-hover:scale-105 transition-transform">
              <AtomIcon className="w-6 h-6 text-white" />
            </div>
            <div>
              <h1 className="font-extrabold text-base sm:text-lg tracking-wider text-transparent bg-clip-text bg-gradient-to-r from-sky-400 to-cyan-200">
                PHYSICS ASSESSMENT
              </h1>
              <p className="text-xs text-slate-400 font-medium hidden sm:block">
                SMAS Alhilaal Tehoru • Yusfyani Rahawarin, S.Pd.
              </p>
            </div>
          </div>

          <div className="flex items-center gap-3">
            {currentScreen === 'exam' && (
              <div className={`flex items-center gap-2 px-3 py-1.5 rounded-lg border font-mono text-sm font-bold shadow-sm transition-colors ${
                timeLeft <= 600 
                  ? 'bg-rose-500/20 border-rose-500 text-rose-300 animate-pulse' 
                  : 'bg-slate-800 border-slate-700 text-sky-300'
              }`}>
                <Clock className="w-4 h-4" />
                <span>{formatTime(timeLeft)}</span>
              </div>
            )}

            <button
              onClick={() => {
                if (isTeacherLoggedIn) {
                  setCurrentScreen('dashboard');
                } else {
                  setShowPinModal(true);
                }
              }}
              className="flex items-center gap-1.5 px-3 py-1.5 text-xs font-semibold rounded-lg bg-slate-800 hover:bg-slate-700 text-slate-300 border border-slate-700 transition-colors"
            >
              <ShieldCheck className="w-4 h-4 text-amber-400" />
              <span>{isTeacherLoggedIn ? 'Dashboard Guru' : 'Akses Guru'}</span>
            </button>
          </div>
        </div>
      </header>

      {/* BODY CONTENT CONTAINER */}
      <main className="max-w-7xl mx-auto px-4 py-6">

        {/* ================= SCREEN 1: WELCOME / HERO ================= */}
        {currentScreen === 'welcome' && (
          <div className="space-y-8 py-6">
            <div className="relative overflow-hidden rounded-3xl bg-gradient-to-b from-slate-900 via-slate-900/90 to-slate-950 border border-slate-800 p-8 sm:p-12 text-center shadow-2xl">
              <div className="absolute -top-24 -left-24 w-72 h-72 bg-sky-500/10 rounded-full blur-3xl pointer-events-none" />
              <div className="absolute -bottom-24 -right-24 w-72 h-72 bg-cyan-500/10 rounded-full blur-3xl pointer-events-none" />
              
              <div className="inline-flex items-center gap-2 px-4 py-1.5 rounded-full bg-sky-500/10 border border-sky-500/30 text-sky-400 text-xs font-semibold mb-6">
                <Sparkles className="w-4 h-4" />
                <span>Media Asesmen Digital Fisika Kelas X</span>
              </div>

              <h1 className="text-3xl sm:text-5xl font-black text-white tracking-tight mb-4 max-w-4xl mx-auto leading-tight">
                Uji Pemahaman Fisika Secara Digital, Presisi & Transparan
              </h1>
              <p className="text-slate-400 text-sm sm:text-base max-w-2xl mx-auto mb-8">
                Materi Evaluasi: Besaran & Satuan, Angka Penting, Pengukuran Alat Ukur, dan Dimensi Besaran untuk SMAS Alhilaal Tehoru.
              </p>

              <div className="flex flex-col sm:flex-row items-center justify-center gap-4">
                <button
                  onClick={() => setCurrentScreen('register')}
                  className="w-full sm:w-auto px-8 py-4 rounded-xl bg-gradient-to-r from-sky-500 to-cyan-500 text-white font-bold text-base shadow-lg shadow-sky-500/25 hover:shadow-sky-500/40 hover:scale-105 transition-all flex items-center justify-center gap-2"
                >
                  <span>MULAI ASESMEN NOW</span>
                  <ChevronRight className="w-5 h-5" />
                </button>
                <button
                  onClick={() => setShowInfoModal(true)}
                  className="w-full sm:w-auto px-6 py-4 rounded-xl bg-slate-800/80 hover:bg-slate-800 text-slate-300 font-semibold text-sm border border-slate-700 transition-colors flex items-center justify-center gap-2"
                >
                  <HelpCircle className="w-4 h-4" />
                  <span>PETUNJUK & INFORMASI</span>
                </button>
              </div>
            </div>

            {/* TOPIC GRID BANNER */}
            <div className="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
              {[
                { title: "Besaran & Satuan", count: "10 Soal", icon: Layers, desc: "Konversi unit SI & klasifikasi besaran" },
                { title: "Angka Penting", count: "10 Soal", icon: Sliders, desc: "Aturan AP & operasi berhitung" },
                { title: "Pengukuran", count: "10 Soal", icon: Target, desc: "Jangka sorong, mikrometer & neraca" },
                { title: "Dimensi Besaran", count: "10 Soal", icon: BarChart3, desc: "Analisis dimensi & pembuktian rumus" },
              ].map((item, idx) => (
                <div key={idx} className="bg-slate-900/60 border border-slate-800 rounded-2xl p-5 hover:border-sky-500/40 transition-colors">
                  <div className="w-10 h-10 rounded-xl bg-sky-500/10 border border-sky-500/20 flex items-center justify-center text-sky-400 mb-4">
                    <item.icon className="w-5 h-5" />
                  </div>
                  <h3 className="font-bold text-white text-base mb-1">{item.title}</h3>
                  <span className="text-xs font-mono font-semibold text-sky-400 bg-sky-500/10 px-2 py-0.5 rounded">
                    {item.count}
                  </span>
                  <p className="text-xs text-slate-400 mt-2">{item.desc}</p>
                </div>
              ))}
            </div>
          </div>
        )}

        {/* ================= SCREEN 2: STUDENT REGISTER ================= */}
        {currentScreen === 'register' && (
          <div className="max-w-md mx-auto py-8">
            <div className="bg-slate-900 border border-slate-800 rounded-3xl p-6 sm:p-8 shadow-xl">
              <div className="flex items-center gap-3 mb-6">
                <div className="w-10 h-10 rounded-xl bg-sky-500/10 border border-sky-500/30 flex items-center justify-center text-sky-400">
                  <User className="w-5 h-5" />
                </div>
                <div>
                  <h2 className="text-xl font-bold text-white">Identitas Peserta Didik</h2>
                  <p className="text-xs text-slate-400">Lengkapi data untuk memulai asesmen</p>
                </div>
              </div>

              <form onSubmit={handleStartExam} className="space-y-5">
                <div>
                  <label className="block text-xs font-medium text-slate-300 mb-1">Nama Lengkap Siswa</label>
                  <input
                    type="text"
                    required
                    placeholder="Contoh: Ahmad Abdullah"
                    value={studentInfo.name}
                    onChange={(e) => setStudentInfo({ ...studentInfo, name: e.target.value })}
                    className="w-full bg-slate-950 border border-slate-700 rounded-xl px-4 py-3 text-white text-sm focus:outline-none focus:border-sky-500 transition-colors"
                  />
                </div>

                <div className="grid grid-cols-2 gap-4">
                  <div>
                    <label className="block text-xs font-medium text-slate-300 mb-1">Kelas</label>
                    <select
                      value={studentInfo.class}
                      onChange={(e) => setStudentInfo({ ...studentInfo, class: e.target.value })}
                      className="w-full bg-slate-950 border border-slate-700 rounded-xl px-4 py-3 text-white text-sm focus:outline-none focus:border-sky-500 transition-colors"
                    >
                      <option value="X-1">X-1</option>
                      <option value="X-2">X-2</option>
                      <option value="X-3">X-3</option>
                      <option value="X-4">X-4</option>
                    </select>
                  </div>

                  <div>
                    <label className="block text-xs font-medium text-slate-300 mb-1">Nomor Absen</label>
                    <input
                      type="number"
                      required
                      placeholder="Misal: 05"
                      value={studentInfo.rollNo}
                      onChange={(e) => setStudentInfo({ ...studentInfo, rollNo: e.target.value })}
                      className="w-full bg-slate-950 border border-slate-700 rounded-xl px-4 py-3 text-white text-sm focus:outline-none focus:border-sky-500 transition-colors"
                    />
                  </div>
                </div>

                <div className="bg-slate-950/60 border border-slate-800 rounded-xl p-4 text-xs text-slate-400 space-y-2">
                  <div className="flex items-center gap-2 text-sky-400 font-semibold">
                    <Clock className="w-4 h-4" /> Durasi Pengerjaan: 60 Menit
                  </div>
                  <p>• Total Soal: 40 Butir Pilihan Ganda (A-E)</p>
                  <p>• Jawaban tersimpan otomatis secara real-time</p>
                </div>

                <div className="flex gap-3 pt-2">
                  <button
                    type="button"
                    onClick={() => setCurrentScreen('welcome')}
                    className="flex-1 py-3 rounded-xl bg-slate-800 hover:bg-slate-700 text-slate-300 font-semibold text-sm transition-colors"
                  >
                    Batal
                  </button>
                  <button
                    type="submit"
                    className="flex-1 py-3 rounded-xl bg-gradient-to-r from-sky-500 to-cyan-500 text-white font-bold text-sm shadow-lg shadow-sky-500/25 hover:shadow-sky-500/40 transition-all flex items-center justify-center gap-2"
                  >
                    <span>MULAI MENGERJAKAN</span>
                    <ArrowRight className="w-4 h-4" />
                  </button>
                </div>
              </form>
            </div>
          </div>
        )}

        {/* ================= SCREEN 3: CBT EXAM INTERFACE ================= */}
        {currentScreen === 'exam' && (
          <div className="space-y-6">
            {/* EXAM NAV BAR */}
            <div className="bg-slate-900 border border-slate-800 rounded-2xl p-4 flex items-center justify-between shadow-md">
              <div className="flex items-center gap-3">
                <div className="w-8 h-8 rounded-lg bg-sky-500/20 text-sky-400 flex items-center justify-center font-bold text-sm">
                  {currentQuestionIndex + 1}
                </div>
                <div>
                  <span className="text-xs text-slate-400 block">Topik Asesmen:</span>
                  <span className="text-xs sm:text-sm font-semibold text-white">
                    {QUESTION_BANK[currentQuestionIndex].topic}
                  </span>
                </div>
              </div>

              <div className="flex items-center gap-2">
                <button
                  onClick={handleToggleFlag}
                  className={`flex items-center gap-1.5 px-3 py-1.5 rounded-lg text-xs font-semibold border transition-colors ${
                    flaggedQuestions[QUESTION_BANK[currentQuestionIndex].id]
                      ? 'bg-amber-500/20 border-amber-500 text-amber-300'
                      : 'bg-slate-800 border-slate-700 text-slate-400 hover:text-white'
                  }`}
                >
                  <Flag className="w-3.5 h-3.5" />
                  <span className="hidden sm:inline">Ragu-ragu</span>
                </button>

                <button
                  onClick={() => setShowQuestionGrid(true)}
                  className="flex items-center gap-1.5 px-3 py-1.5 rounded-lg bg-slate-800 hover:bg-slate-700 text-sky-400 border border-slate-700 text-xs font-semibold transition-colors"
                >
                  <Layers className="w-3.5 h-3.5" />
                  <span>Daftar Soal ({Object.keys(userAnswers).length}/40)</span>
                </button>
              </div>
            </div>

            {/* QUESTION CARD */}
            <div className="bg-slate-900 border border-slate-800 rounded-3xl p-6 sm:p-8 shadow-xl min-h-[400px] flex flex-col justify-between">
              <div className="space-y-4">
                <h3 className="text-base sm:text-lg font-medium text-slate-100 leading-relaxed">
                  <span className="font-bold text-sky-400 mr-2">{currentQuestionIndex + 1}.</span>
                  {QUESTION_BANK[currentQuestionIndex].question}
                </h3>

                {/* Render Instrument Diagram if available */}
                {QUESTION_BANK[currentQuestionIndex].visualType && 
                  renderInstrumentVisual(
                    QUESTION_BANK[currentQuestionIndex].visualType,
                    QUESTION_BANK[currentQuestionIndex].visualData
                  )
                }

                {/* OPTIONS */}
                <div className="space-y-3 pt-2">
                  {QUESTION_BANK[currentQuestionIndex].options.map((opt, optIdx) => {
                    const isSelected = userAnswers[QUESTION_BANK[currentQuestionIndex].id] === optIdx;
                    return (
                      <div
                        key={optIdx}
                        onClick={() => handleSelectOption(optIdx)}
                        className={`p-4 rounded-xl border text-sm cursor-pointer transition-all flex items-center justify-between ${
                          isSelected
                            ? 'bg-sky-500/15 border-sky-500 text-white shadow-md shadow-sky-500/10'
                            : 'bg-slate-950/60 border-slate-800 hover:border-slate-700 text-slate-300'
                        }`}
                      >
                        <span>{opt}</span>
                        <div className={`w-5 h-5 rounded-full border flex items-center justify-center transition-colors ${
                          isSelected ? 'border-sky-400 bg-sky-500 text-white' : 'border-slate-700'
                        }`}>
                          {isSelected && <Check className="w-3 h-3 stroke-[3]" />}
                        </div>
                      </div>
                    );
                  })}
                </div>
              </div>

              {/* FOOTER ACTIONS */}
              <div className="flex items-center justify-between pt-8 border-t border-slate-800 mt-6">
                <button
                  disabled={currentQuestionIndex === 0}
                  onClick={() => setCurrentQuestionIndex(prev => prev - 1)}
                  className="px-4 py-2.5 rounded-xl bg-slate-800 hover:bg-slate-700 disabled:opacity-40 disabled:cursor-not-allowed text-slate-300 font-semibold text-xs sm:text-sm flex items-center gap-2 transition-colors"
                >
                  <ChevronLeft className="w-4 h-4" />
                  <span>Sebelumnya</span>
                </button>

                {currentQuestionIndex < QUESTION_BANK.length - 1 ? (
                  <button
                    onClick={() => setCurrentQuestionIndex(prev => prev + 1)}
                    className="px-5 py-2.5 rounded-xl bg-sky-600 hover:bg-sky-500 text-white font-semibold text-xs sm:text-sm flex items-center gap-2 transition-colors"
                  >
                    <span>Berikutnya</span>
                    <ChevronRight className="w-4 h-4" />
                  </button>
                ) : (
                  <button
                    onClick={() => setShowSubmitModal(true)}
                    className="px-6 py-2.5 rounded-xl bg-emerald-600 hover:bg-emerald-500 text-white font-bold text-xs sm:text-sm shadow-lg shadow-emerald-600/20 flex items-center gap-2 transition-colors"
                  >
                    <span>SELESAI & KUMPULKAN</span>
                    <CheckCircle2 className="w-4 h-4" />
                  </button>
                )}
              </div>
            </div>
          </div>
        )}

        {/* ================= SCREEN 4: RESULT SCREEN ================= */}
        {currentScreen === 'result' && currentResultRecord && (
          <div className="max-w-4xl mx-auto space-y-8 py-4">
            {/* OFFICIAL RESULT CARD */}
            <div className="bg-slate-900 border border-slate-800 rounded-3xl p-6 sm:p-10 shadow-2xl relative overflow-hidden">
              <div className="absolute top-0 right-0 w-48 h-48 bg-sky-500/10 rounded-full blur-3xl" />
              
              <div className="text-center space-y-4 mb-8">
                <div className="inline-flex items-center gap-2 px-4 py-1.5 rounded-full bg-emerald-500/10 border border-emerald-500/30 text-emerald-400 text-xs font-semibold">
                  <CheckCircle2 className="w-4 h-4" /> Asesmen Berhasil Dikumpulkan
                </div>
                <h2 className="text-2xl sm:text-3xl font-black text-white">
                  Laporan Hasil Asesmen Fisika
                </h2>
                <p className="text-xs text-slate-400">
                  SMAS Alhilaal Tehoru • Guru Pengampu: Yusfyani Rahawarin, S.Pd.
                </p>
              </div>

              {/* SCORE BANNER */}
              <div className="grid grid-cols-1 sm:grid-cols-3 gap-6 bg-slate-950 border border-slate-800 rounded-2xl p-6 mb-8 text-center">
                <div className="space-y-1">
                  <span className="text-xs text-slate-400 block">NILAI AKHIR</span>
                  <span className="text-4xl sm:text-5xl font-black text-transparent bg-clip-text bg-gradient-to-r from-sky-400 to-cyan-300">
                    {currentResultRecord.score}
                  </span>
                  <span className="text-xs text-slate-500 block">dari 100 poin</span>
                </div>
                
                <div className="space-y-1 border-y sm:border-y-0 sm:border-x border-slate-800 py-4 sm:py-0">
                  <span className="text-xs text-slate-400 block">PREDIKAT</span>
                  <span className={`text-xl font-bold block ${
                    currentResultRecord.score >= 80 ? 'text-emerald-400' :
                    currentResultRecord.score >= 70 ? 'text-amber-400' : 'text-rose-400'
                  }`}>
                    {currentResultRecord.predicate}
                  </span>
                  <span className="text-xs text-slate-500 block">Kriteria Kelulusan</span>
                </div>

                <div className="space-y-1">
                  <span className="text-xs text-slate-400 block">JAWABAN BENAR</span>
                  <span className="text-2xl font-bold text-white block">
                    {currentResultRecord.correctCount} / {currentResultRecord.totalQuestions}
                  </span>
                  <span className="text-xs text-slate-500 block">Soal Pilihan Ganda</span>
                </div>
              </div>

              {/* STUDENT METADATA */}
              <div className="grid grid-cols-2 sm:grid-cols-4 gap-4 bg-slate-950/50 p-4 rounded-xl border border-slate-800 text-xs mb-8">
                <div>
                  <span className="text-slate-500 block">Nama Siswa:</span>
                  <span className="font-semibold text-slate-200">{currentResultRecord.studentInfo.name}</span>
                </div>
                <div>
                  <span className="text-slate-500 block">Kelas / Absen:</span>
                  <span className="font-semibold text-slate-200">{currentResultRecord.studentInfo.class} / #{currentResultRecord.studentInfo.rollNo}</span>
                </div>
                <div>
                  <span className="text-slate-500 block">Tanggal Pengerjaan:</span>
                  <span className="font-semibold text-slate-200">{currentResultRecord.date}</span>
                </div>
                <div>
                  <span className="text-slate-500 block">Waktu Digunakan:</span>
                  <span className="font-semibold text-slate-200">{Math.floor(currentResultRecord.durationSpent / 60)} m {currentResultRecord.durationSpent % 60} s</span>
                </div>
              </div>

              {/* TOPIC BREAKDOWN */}
              <div className="space-y-3 mb-8">
                <h4 className="text-sm font-bold text-white">Analisis Penguasaan Materi:</h4>
                <div className="grid grid-cols-1 sm:grid-cols-2 gap-4">
                  {Object.entries(currentResultRecord.topicBreakdown).map(([topName, topData], idx) => {
                    const pct = Math.round((topData.correct / topData.total) * 100);
                    return (
                      <div key={idx} className="bg-slate-950 p-4 rounded-xl border border-slate-800 space-y-2">
                        <div className="flex justify-between text-xs">
                          <span className="font-medium text-slate-300">{topName}</span>
                          <span className="font-bold text-sky-400">{topData.correct}/{topData.total} ({pct}%)</span>
                        </div>
                        <div className="w-full bg-slate-800 h-2 rounded-full overflow-hidden">
                          <div 
                            className="bg-gradient-to-r from-sky-500 to-cyan-400 h-full rounded-full"
                            style={{ width: `${pct}%` }}
                          />
                        </div>
                      </div>
                    );
                  })}
                </div>
              </div>

              {/* ACTION BUTTONS */}
              <div className="flex flex-col sm:flex-row gap-4">
                <button
                  onClick={() => setCurrentScreen('review')}
                  className="flex-1 py-3.5 rounded-xl bg-sky-600 hover:bg-sky-500 text-white font-bold text-sm shadow-lg shadow-sky-600/20 transition-all flex items-center justify-center gap-2"
                >
                  <Eye className="w-4 h-4" />
                  <span>LIHAT PEMBAHASAN SOAL</span>
                </button>
                <button
                  onClick={() => window.print()}
                  className="flex-1 py-3.5 rounded-xl bg-slate-800 hover:bg-slate-700 text-slate-200 font-semibold text-sm border border-slate-700 transition-colors flex items-center justify-center gap-2"
                >
                  <Printer className="w-4 h-4" />
                  <span>CETAK HASIL ASESMEN</span>
                </button>
                <button
                  onClick={() => setCurrentScreen('welcome')}
                  className="py-3.5 px-6 rounded-xl bg-slate-950 hover:bg-slate-800 text-slate-400 font-medium text-sm border border-slate-800 transition-colors flex items-center justify-center gap-2"
                >
                  <RotateCcw className="w-4 h-4" />
                  <span>Beranda</span>
                </button>
              </div>
            </div>
          </div>
        )}

        {/* ================= SCREEN 5: REVIEW / PEMBAHASAN ================= */}
        {currentScreen === 'review' && currentResultRecord && (
          <div className="max-w-4xl mx-auto space-y-6 py-4">
            <div className="flex items-center justify-between bg-slate-900 p-4 rounded-2xl border border-slate-800">
              <div>
                <h2 className="font-bold text-white text-lg">Pembahasan Soal Lengkap</h2>
                <p className="text-xs text-slate-400">
                  Siswa: {currentResultRecord.studentInfo.name} ({currentResultRecord.studentInfo.class})
                </p>
              </div>
              <button
                onClick={() => setCurrentScreen('result')}
                className="px-4 py-2 rounded-xl bg-slate-800 hover:bg-slate-700 text-slate-300 text-xs font-semibold border border-slate-700 transition-colors"
              >
                Kembali ke Ringkasan
              </button>
            </div>

            <div className="space-y-6">
              {QUESTION_BANK.map((q, qIdx) => {
                const studentAns = currentResultRecord.userAnswers[q.id];
                const isCorrect = studentAns === q.correctAnswer;
                return (
                  <div key={q.id} className="bg-slate-900 border border-slate-800 rounded-2xl p-6 space-y-4">
                    <div className="flex items-start justify-between gap-4">
                      <span className="text-xs font-bold px-3 py-1 rounded-full bg-slate-800 text-sky-400">
                        {q.topic} • Soal #{qIdx + 1}
                      </span>
                      {isCorrect ? (
                        <span className="inline-flex items-center gap-1 text-xs font-bold text-emerald-400 bg-emerald-500/10 px-3 py-1 rounded-full border border-emerald-500/30">
                          <CheckCircle2 className="w-3.5 h-3.5" /> Benar (+2,5)
                        </span>
                      ) : (
                        <span className="inline-flex items-center gap-1 text-xs font-bold text-rose-400 bg-rose-500/10 px-3 py-1 rounded-full border border-rose-500/30">
                          <XCircle className="w-3.5 h-3.5" /> Salah / Kosong
                        </span>
                      )}
                    </div>

                    <p className="text-sm font-medium text-slate-100">{q.question}</p>

                    {q.visualType && renderInstrumentVisual(q.visualType, q.visualData)}

                    <div className="space-y-2">
                      {q.options.map((opt, optIdx) => {
                        const isStudentChoice = studentAns === optIdx;
                        const isRightAnswer = q.correctAnswer === optIdx;

                        let optBg = "bg-slate-950/60 border-slate-800 text-slate-400";
                        if (isRightAnswer) optBg = "bg-emerald-500/15 border-emerald-500 text-emerald-300 font-medium";
                        else if (isStudentChoice && !isCorrect) optBg = "bg-rose-500/15 border-rose-500 text-rose-300";

                        return (
                          <div key={optIdx} className={`p-3 rounded-xl border text-xs flex items-center justify-between ${optBg}`}>
                            <span>{opt}</span>
                            {isRightAnswer && <span className="font-bold text-emerald-400">Kunci Jawaban</span>}
                            {isStudentChoice && !isRightAnswer && <span className="font-bold text-rose-400">Jawaban Anda</span>}
                          </div>
                        );
                      })}
                    </div>

                    <div className="bg-slate-950 p-4 rounded-xl border border-slate-800 text-xs space-y-1.5">
                      <span className="font-bold text-sky-400 block">Langkah Pembahasan Scientific:</span>
                      <p className="text-slate-300 whitespace-pre-line leading-relaxed">{q.explanation}</p>
                    </div>
                  </div>
                );
              })}
            </div>
          </div>
        )}

        {/* ================= SCREEN 6: TEACHER DASHBOARD ================= */}
        {currentScreen === 'dashboard' && isTeacherLoggedIn && (
          <div className="space-y-8 py-4">
            <div className="flex flex-col sm:flex-row items-start sm:items-center justify-between gap-4 bg-slate-900 p-6 rounded-3xl border border-slate-800">
              <div>
                <h2 className="text-xl font-bold text-white flex items-center gap-2">
                  <ShieldCheck className="w-5 h-5 text-amber-400" />
                  Dashboard Penilaian Guru Fisika
                </h2>
                <p className="text-xs text-slate-400 mt-1">
                  Pengelola Asesmen SMAS Alhilaal Tehoru • Yusfyani Rahawarin, S.Pd.
                </p>
              </div>
              <button
                onClick={() => {
                  setIsTeacherLoggedIn(false);
                  setCurrentScreen('welcome');
                }}
                className="px-4 py-2 rounded-xl bg-rose-500/10 hover:bg-rose-500/20 text-rose-300 text-xs font-semibold border border-rose-500/30 transition-colors flex items-center gap-1.5"
              >
                <LogOut className="w-4 h-4" /> Logout Guru
              </button>
            </div>

            {/* DASHBOARD STAT CARDS */}
            <div className="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
              <div className="bg-slate-900 border border-slate-800 rounded-2xl p-5">
                <div className="flex items-center justify-between text-slate-400 text-xs mb-2">
                  <span>Total Peserta Ujian</span>
                  <Users className="w-4 h-4 text-sky-400" />
                </div>
                <span className="text-3xl font-black text-white">{savedRecords.length}</span>
                <span className="text-[10px] text-slate-500 block mt-1">Siswa telah submit</span>
              </div>

              <div className="bg-slate-900 border border-slate-800 rounded-2xl p-5">
                <div className="flex items-center justify-between text-slate-400 text-xs mb-2">
                  <span>Rata-Rata Nilai</span>
                  <TrendingUp className="w-4 h-4 text-emerald-400" />
                </div>
                <span className="text-3xl font-black text-emerald-400">
                  {savedRecords.length > 0 
                    ? Math.round(savedRecords.reduce((acc, r) => acc + r.score, 0) / savedRecords.length)
                    : 0}
                </span>
                <span className="text-[10px] text-slate-500 block mt-1">Skala 0-100</span>
              </div>

              <div className="bg-slate-900 border border-slate-800 rounded-2xl p-5">
                <div className="flex items-center justify-between text-slate-400 text-xs mb-2">
                  <span>Nilai Tertinggi</span>
                  <Award className="w-4 h-4 text-amber-400" />
                </div>
                <span className="text-3xl font-black text-amber-400">
                  {savedRecords.length > 0 ? Math.max(...savedRecords.map(r => r.score)) : 0}
                </span>
                <span className="text-[10px] text-slate-500 block mt-1">Skor maksimum</span>
              </div>

              <div className="bg-slate-900 border border-slate-800 rounded-2xl p-5">
                <div className="flex items-center justify-between text-slate-400 text-xs mb-2">
                  <span>Tingkat Kelulusan</span>
                  <Target className="w-4 h-4 text-cyan-400" />
                </div>
                <span className="text-3xl font-black text-cyan-400">
                  {savedRecords.length > 0
                    ? Math.round((savedRecords.filter(r => r.score >= 70).length / savedRecords.length) * 100)
                    : 0}%
                </span>
                <span className="text-[10px] text-slate-500 block mt-1">KKM ≥ 70</span>
              </div>
            </div>

            {/* TABLE CONTROLS */}
            <div className="bg-slate-900 border border-slate-800 rounded-2xl p-6 space-y-4">
              <div className="flex flex-col sm:flex-row items-center justify-between gap-4">
                <h3 className="font-bold text-white text-base">Daftar Hasil Nilai Peserta Didik</h3>
                
                <div className="flex items-center gap-3 w-full sm:w-auto">
                  <div className="relative flex-1 sm:w-64">
                    <Search className="w-4 h-4 absolute left-3 top-3 text-slate-500" />
                    <input
                      type="text"
                      placeholder="Cari nama siswa..."
                      value={searchQuery}
                      onChange={(e) => setSearchQuery(e.target.value)}
                      className="w-full bg-slate-950 border border-slate-800 rounded-xl pl-9 pr-4 py-2 text-xs text-white focus:outline-none focus:border-sky-500"
                    />
                  </div>

                  <select
                    value={classFilter}
                    onChange={(e) => setClassFilter(e.target.value)}
                    className="bg-slate-950 border border-slate-800 rounded-xl px-3 py-2 text-xs text-white focus:outline-none focus:border-sky-500"
                  >
                    <option value="ALL font-sans">Semua Kelas</option>
                    <option value="X-1">Kelas X-1</option>
                    <option value="X-2">Kelas X-2</option>
                    <option value="X-3">Kelas X-3</option>
                    <option value="X-4">Kelas X-4</option>
                  </select>

                  <button
                    onClick={() => {
                      const csvContent = "data:text/csv;charset=utf-8," 
                        + ["Nama,Kelas,Absen,Nilai,Predikat,Tanggal"]
                          .concat(savedRecords.map(r => `"${r.studentInfo.name}","${r.studentInfo.class}","${r.studentInfo.rollNo}",${r.score},"${r.predicate}","${r.date}"`))
                          .join("\n");
                      const encodedUri = encodeURI(csvContent);
                      const link = document.createElement("a");
                      link.setAttribute("href", encodedUri);
                      link.setAttribute("download", `Rekap_Nilai_Fisika_X_${Date.now()}.csv`);
                      document.body.appendChild(link);
                      link.click();
                      document.body.removeChild(link);
                    }}
                    className="px-3 py-2 bg-emerald-600 hover:bg-emerald-500 text-white text-xs font-semibold rounded-xl flex items-center gap-1.5 transition-colors"
                  >
                    <FileSpreadsheet className="w-4 h-4" /> CSV
                  </button>
                </div>
              </div>

              {/* ROSTER TABLE */}
              <div className="overflow-x-auto">
                <table className="w-full text-left text-xs border-collapse">
                  <thead>
                    <tr className="bg-slate-950 border-b border-slate-800 text-slate-400">
                      <th className="p-3">No</th>
                      <th className="p-3">Nama Siswa</th>
                      <th className="p-3">Kelas</th>
                      <th className="p-3">Absen</th>
                      <th className="p-3">Nilai</th>
                      <th className="p-3">Predikat</th>
                      <th className="p-3">Tanggal & Waktu</th>
                    </tr>
                  </thead>
                  <tbody className="divide-y divide-slate-800 text-slate-300">
                    {savedRecords
                      .filter(r => classFilter === 'ALL' || r.studentInfo.class === classFilter)
                      .filter(r => r.studentInfo.name.toLowerCase().includes(searchQuery.toLowerCase()))
                      .map((rec, idx) => (
                        <tr key={rec.id} className="hover:bg-slate-850 transition-colors">
                          <td className="p-3 font-mono text-slate-500">{idx + 1}</td>
                          <td className="p-3 font-bold text-white">{rec.studentInfo.name}</td>
                          <td className="p-3">{rec.studentInfo.class}</td>
                          <td className="p-3 font-mono">#{rec.studentInfo.rollNo}</td>
                          <td className="p-3 font-bold text-sky-400 text-sm font-mono">{rec.score}</td>
                          <td className="p-3">
                            <span className={`px-2 py-0.5 rounded text-[10px] font-bold ${
                              rec.score >= 80 ? 'bg-emerald-500/10 text-emerald-400 border border-emerald-500/30' :
                              rec.score >= 70 ? 'bg-amber-500/10 text-amber-400 border border-amber-500/30' : 'bg-rose-500/10 text-rose-400 border border-rose-500/30'
                            }`}>
                              {rec.predicate}
                            </span>
                          </td>
                          <td className="p-3 text-slate-400">{rec.date}</td>
                        </tr>
                      ))}
                  </tbody>
                </table>
              </div>
            </div>
          </div>
        )}

      </main>

      {/* ================= MODAL: QUESTION GRID / DRAWER ================= */}
      {showQuestionGrid && (
        <div className="fixed inset-0 z-50 bg-slate-950/80 backdrop-blur-sm flex items-center justify-center p-4">
          <div className="bg-slate-900 border border-slate-800 rounded-3xl max-w-lg w-full p-6 space-y-6 shadow-2xl">
            <div className="flex items-center justify-between border-b border-slate-800 pb-4">
              <h3 className="font-bold text-white text-base">Navigasi Lembar Soal</h3>
              <button 
                onClick={() => setShowQuestionGrid(false)}
                className="text-slate-400 hover:text-white"
              >
                <XCircle className="w-5 h-5" />
              </button>
            </div>

            <div className="grid grid-cols-5 sm:grid-cols-8 gap-2.5 max-h-80 overflow-y-auto p-1">
              {QUESTION_BANK.map((q, idx) => {
                const isAnswered = userAnswers[q.id] !== undefined;
                const isFlagged = flaggedQuestions[q.id];
                const isCurrent = currentQuestionIndex === idx;

                let btnBg = "bg-slate-950 border-slate-800 text-slate-400";
                if (isCurrent) btnBg = "bg-sky-500 border-sky-400 text-white font-bold ring-2 ring-sky-400/50";
                else if (isFlagged) btnBg = "bg-amber-500/20 border-amber-500 text-amber-300";
                else if (isAnswered) btnBg = "bg-emerald-500/20 border-emerald-500 text-emerald-300";

                return (
                  <button
                    key={q.id}
                    onClick={() => {
                      setCurrentQuestionIndex(idx);
                      setShowQuestionGrid(false);
                    }}
                    className={`h-10 rounded-xl border font-mono text-xs font-bold transition-all flex items-center justify-center ${btnBg}`}
                  >
                    {idx + 1}
                  </button>
                );
              })}
            </div>

            <div className="flex items-center justify-around text-xs text-slate-400 pt-2 border-t border-slate-800">
              <span className="flex items-center gap-1.5">
                <span className="w-3 h-3 rounded bg-emerald-500/30 border border-emerald-500" /> Dijawab
              </span>
              <span className="flex items-center gap-1.5">
                <span className="w-3 h-3 rounded bg-amber-500/30 border border-amber-500" /> Ragu-ragu
              </span>
              <span className="flex items-center gap-1.5">
                <span className="w-3 h-3 rounded bg-slate-950 border border-slate-800" /> Belum
              </span>
            </div>
          </div>
        </div>
      )}

      {/* ================= MODAL: SUBMIT CONFIRMATION ================= */}
      {showSubmitModal && (
        <div className="fixed inset-0 z-50 bg-slate-950/80 backdrop-blur-sm flex items-center justify-center p-4">
          <div className="bg-slate-900 border border-slate-800 rounded-3xl max-w-md w-full p-6 space-y-6 text-center shadow-2xl">
            <div className="w-12 h-12 rounded-full bg-amber-500/10 border border-amber-500/30 text-amber-400 flex items-center justify-center mx-auto">
              <AlertCircle className="w-6 h-6" />
            </div>

            <div className="space-y-2">
              <h3 className="font-bold text-white text-lg">Kumpulkan Jawaban Asesmen?</h3>
              <p className="text-xs text-slate-400">
                Anda telah menjawab <span className="text-sky-400 font-bold">{Object.keys(userAnswers).length}</span> dari <span className="text-white font-bold">40</span> soal. Jawaban yang dikumpulkan tidak dapat diubah kembali.
              </p>
            </div>

            <div className="flex gap-3">
              <button
                onClick={() => setShowSubmitModal(false)}
                className="flex-1 py-3 rounded-xl bg-slate-800 hover:bg-slate-700 text-slate-300 font-semibold text-xs transition-colors"
              >
                Kembali Pengerjaan
              </button>
              <button
                onClick={processSubmit}
                className="flex-1 py-3 rounded-xl bg-emerald-600 hover:bg-emerald-500 text-white font-bold text-xs shadow-lg shadow-emerald-600/25 transition-all"
              >
                Ya, Kumpulkan Now
              </button>
            </div>
          </div>
        </div>
      )}

      {/* ================= MODAL: TEACHER PIN AUTH ================= */}
      {showPinModal && (
        <div className="fixed inset-0 z-50 bg-slate-950/80 backdrop-blur-sm flex items-center justify-center p-4">
          <div className="bg-slate-900 border border-slate-800 rounded-3xl max-w-xs w-full p-6 space-y-4 shadow-2xl">
            <div className="text-center space-y-1">
              <div className="w-10 h-10 rounded-xl bg-amber-500/10 text-amber-400 flex items-center justify-center mx-auto mb-2">
                <Lock className="w-5 h-5" />
              </div>
              <h3 className="font-bold text-white text-base">Autentikasi Guru</h3>
              <p className="text-[11px] text-slate-400">Masukan PIN untuk membuka rekap penilaian</p>
            </div>

            <form onSubmit={handleTeacherLogin} className="space-y-3">
              <input
                type="password"
                required
                placeholder="PIN (Default: 12345)"
                value={teacherPinInput}
                onChange={(e) => setTeacherPinInput(e.target.value)}
                className="w-full bg-slate-950 border border-slate-700 rounded-xl px-4 py-2.5 text-center text-white text-sm font-mono focus:outline-none focus:border-amber-500"
              />

              {pinError && <p className="text-[10px] text-rose-400 text-center font-medium">{pinError}</p>}

              <div className="flex gap-2">
                <button
                  type="button"
                  onClick={() => setShowPinModal(false)}
                  className="flex-1 py-2 rounded-xl bg-slate-800 text-slate-400 text-xs"
                >
                  Batal
                </button>
                <button
                  type="submit"
                  className="flex-1 py-2 rounded-xl bg-amber-500 hover:bg-amber-400 text-slate-950 font-bold text-xs"
                >
                  Masuk
                </button>
              </div>
            </form>
          </div>
        </div>
      )}

      {/* ================= MODAL: INFO / PETUNJUK ================= */}
      {showInfoModal && (
        <div className="fixed inset-0 z-50 bg-slate-950/80 backdrop-blur-sm flex items-center justify-center p-4">
          <div className="bg-slate-900 border border-slate-800 rounded-3xl max-w-lg w-full p-6 space-y-4 text-xs text-slate-300 shadow-2xl">
            <div className="flex items-center justify-between border-b border-slate-800 pb-3">
              <h3 className="font-bold text-white text-sm flex items-center gap-2">
                <HelpCircle className="w-4 h-4 text-sky-400" /> Petunjuk Teknis Asesmen Digital
              </h3>
              <button onClick={() => setShowInfoModal(false)} className="text-slate-400 hover:text-white">
                <XCircle className="w-5 h-5" />
              </button>
            </div>

            <div className="space-y-3 max-h-80 overflow-y-auto pr-1">
              <p><strong>1. Identitas:</strong> Isikan nama lengkap dan nomor absen dengan tepat sebelum menekan tombol Mulai.</p>
              <p><strong>2. Durasi Waktu:</strong> Waktu pengerjaan dialokasikan 60 menit. Timer berjalan otomatis di pojok kanan atas.</p>
              <p><strong>3. Navigasi Soal:</strong> Gunakan tombol "Berikutnya" / "Sebelumnya" atau "Daftar Soal" untuk berpindah nomor secara cepat.</p>
              <p><strong>4. Penilaian:</strong> Setiap soal memiliki bobot sama. Nilai diproses otomatis dengan rumus: <code>(Jawaban Benar / 40) × 100</code>.</p>
              <p><strong>5. Pembahasan:</strong> Setelah menyelesaikan asesmen, siswa dapat mempelajari langkah penyelesaian scientific lengkap.</p>
            </div>

            <button
              onClick={() => setShowInfoModal(false)}
              className="w-full py-2.5 rounded-xl bg-sky-600 hover:bg-sky-500 text-white font-bold text-xs transition-colors"
            >
              Saya Mengerti
            </button>
          </div>
        </div>
      )}

      {/* PRINT CERTIFICATE TEMPLATE (@media print ONLY) */}
      {currentResultRecord && (
        <div className="hidden print:block fixed inset-0 bg-white text-slate-900 p-12 space-y-8 font-serif">
          <div className="text-center border-b-4 border-slate-900 pb-6">
            <h1 className="text-3xl font-black tracking-wider uppercase">SMAS ALHILAAL TEHORU</h1>
            <p className="text-sm font-sans">KECAMATAN TEHORU, KABUPATEN MALUKU TENGAH</p>
            <p className="text-xs font-sans text-slate-600 mt-1">LEMBAR HASIL EVALUASI PEMBELAJARAN FISIKA DIGITAL (ASESMEN KELAS X)</p>
          </div>

          <div className="space-y-4 font-sans text-sm">
            <div className="grid grid-cols-2 gap-4 bg-slate-100 p-4 rounded-lg">
              <div><strong>Nama Siswa:</strong> {currentResultRecord.studentInfo.name}</div>
              <div><strong>Kelas / Nomor Absen:</strong> {currentResultRecord.studentInfo.class} / #{currentResultRecord.studentInfo.rollNo}</div>
              <div><strong>Mata Pelajaran:</strong> Fisika (Besaran, AP, Pengukuran, Dimensi)</div>
              <div><strong>Tanggal Pelaksanaan:</strong> {currentResultRecord.date}</div>
            </div>

            <div className="border-2 border-slate-900 p-6 rounded-xl text-center space-y-2">
              <span className="text-xs uppercase tracking-widest font-bold text-slate-600">NILAI AKHIR ASESMEN</span>
              <div className="text-6xl font-black">{currentResultRecord.score} / 100</div>
              <div className="text-lg font-bold">PREDIKAT: {currentResultRecord.predicate}</div>
            </div>
          </div>

          <div className="flex justify-between items-end pt-16 font-sans text-xs">
            <div className="text-center">
              <p>Orang Tua / Wali Siswa</p>
              <div className="h-16" />
              <p className="font-bold border-t border-slate-400 pt-1 px-8">( ............................................ )</p>
            </div>

            <div className="text-center">
              <p>Tehoru, {currentResultRecord.date.split(',')[0]}</p>
              <p>Guru Pengampu Fisika</p>
              <div className="h-16 flex items-center justify-center italic text-slate-400">
                [ Tanda Tangan Digital ]
              </div>
              <p className="font-bold border-t border-slate-400 pt-1 px-4">Yusfyani Rahawarin, S.Pd.</p>
            </div>
          </div>
        </div>
      )}
    </div>
  );
}

// Atom Icon SVG
function AtomIcon(props) {
  return (
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" {...props}>
      <circle cx="12" cy="12" r="2" />
      <path d="M12 2v20M2 12h20" opacity="0.3" />
      <path d="M4.93 4.93 M19.07 19.07" opacity="0.3" />
      <ellipse cx="12" cy="12" rx="9" ry="3" transform="rotate(30 12 12)" />
      <ellipse cx="12" cy="12" rx="9" ry="3" transform="rotate(150 12 12)" />
    </svg>
  );
}