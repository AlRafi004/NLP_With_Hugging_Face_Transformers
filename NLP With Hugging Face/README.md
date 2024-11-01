# Analisis Teknik NLP Menggunakan Transformers

## Deskripsi
Proyek ini berisi analisis tentang berbagai teknik Natural Language Processing (NLP) yang digunakan dalam pemodelan bahasa menggunakan library Transformers dari Hugging Face. Teknik yang dianalisis meliputi klasifikasi zero-shot, pembuatan teks, pengisian kata yang hilang (fill-mask), pengenalan entitas bernama (NER), menjawab pertanyaan (question-answering), analisis sentimen, ringkasan (summarization), dan terjemahan (translation).

## Daftar Isi
- [1. Zero-Shot Classification](#zero-shot-classification)
- [2. Text Generation](#text-generation)
- [3. Fill-Mask](#fill-mask)
- [4. Named Entity Recognition (NER)](#named-entity-recognition-ner)
- [5. Question-Answering](#question-answering)
- [6. Sentiment Analysis](#sentiment-analysis)
- [7. Summarization](#summarization)
- [8. Translation](#translation)

## 1. Zero-Shot Classification
Zero-shot classification adalah teknik yang memungkinkan model untuk mengklasifikasikan teks ke dalam kategori yang belum pernah dilihat sebelumnya. Dalam contoh ini, model berhasil mengidentifikasi sentimen negatif dari teks yang menyatakan ketidakpuasan terhadap layanan restoran.

## 2. Text Generation
Text generation menciptakan teks baru berdasarkan input yang diberikan. Dengan menggunakan model yang berbeda, contoh ini menunjukkan kemampuan model untuk menghasilkan kalimat yang relevan dan kreatif, menyoroti fleksibilitas dalam menghasilkan konten.

## 3. Fill-Mask
Fill-mask digunakan untuk memprediksi kata yang hilang dalam sebuah kalimat. Dalam analisis ini, model dapat dengan tepat mengisi kata yang hilang berdasarkan konteks kalimat, menunjukkan pemahaman model terhadap struktur bahasa.

## 4. Named Entity Recognition (NER)
NER mengidentifikasi dan mengklasifikasikan entitas dalam teks. Contoh ini menunjukkan bagaimana model dapat mengenali nama orang, tempat, dan organisasi dalam kalimat, sangat berguna dalam analisis data teks.

## 5. Question-Answering
Question-answering memungkinkan pengguna untuk mendapatkan jawaban atas pertanyaan berdasarkan konteks yang diberikan. Dua contoh menunjukkan kemampuan model untuk menjawab pertanyaan dengan akurat, mendemonstrasikan penerapan dalam bidang pendidikan dan kesehatan.

## 6. Sentiment Analysis
Sentiment analysis mengidentifikasi emosi dalam teks, seperti positif, negatif, atau netral. Analisis menunjukkan bagaimana model dapat mengenali dan mengklasifikasikan perasaan dalam kalimat secara otomatis.

## 7. Summarization
Summarization menghasilkan ringkasan dari teks panjang, menjaga informasi penting. Dalam contoh ini, model berhasil merangkum dampak AI pada berbagai sektor, memberikan pandangan singkat yang berguna.

## 8. Translation
Translation menerjemahkan teks dari satu bahasa ke bahasa lain. Contoh ini menunjukkan bagaimana model dapat menerjemahkan kalimat dari bahasa Prancis ke bahasa Inggris dengan akurasi yang tinggi.

## Cara Menggunakan
1. Clone repositori ini ke komputer Anda.
2. Pastikan Anda memiliki Python dan library Transformers terinstal atau lebih mudahnya gunakan saja Google Collab.
3. Jalankan skrip di dalam direktori proyek untuk melihat hasil analisis.

## Lisensi
Proyek ini dilisensikan di bawah MIT License. Lihat file LICENSE untuk detail lebih lanjut.