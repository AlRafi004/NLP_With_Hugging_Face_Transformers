<div align="center">

# Analisis Teknik NLP Menggunakan Transformers

Proyek ini berisi analisis tentang berbagai teknik Natural Language Processing (NLP) yang digunakan dalam pemodelan bahasa menggunakan library Transformers dari Hugging Face. Teknik yang dianalisis meliputi klasifikasi zero-shot, pembuatan teks, pengisian kata yang hilang (fill-mask), pengenalan entitas bernama (NER), menjawab pertanyaan (question-answering), analisis sentimen, ringkasan (summarization), dan terjemahan (translation).

<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
<img src="https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white">

============================================================================================
</div>

## Daftar Isi
- [1. Zero-Shot Classification](#zero-shot-classification)
- [2. Text Generation](#text-generation)
- [3. Fill Mask](#fill-mask)
- [4. Named Entity Recognition (NER)](#named-entity-recognition-ner)
- [5. Question Answering](#question-answering)
- [6. Sentiment Analysis](#sentiment-analysis)
- [7. Summarization](#summarization)
- [8. Translation](#translation)

===========================================================================

## Zero-Shot Classification
<p align="justify">
Zero-shot classification adalah metode yang memungkinkan model untuk mengidentifikasi teks ke dalam kategori yang belum dikenali sebelumnya, berdasar pada konteks dan label kandidat yang relevan. Pada contoh yang telah dibuat, model klasifikasi zero-shot berhasil menentukan kategori yang paling relevan dengan konten teks meski kategori tersebut tidak dilatih secara spesifik sebelumnya. Contohnya, model mampu mengidentifikasi bahwa tema mengenai kecerdasan buatan berhubungan dengan "teknologi" atau bahwa diskusi tentang perubahan iklim sejalan dengan label "pemanasan global." Dengan demikian, model ini mampu secara adaptif menentukan label yang paling akurat tanpa memerlukan pelatihan tambahan, sehingga ideal untuk situasi yang memerlukan klasifikasi yang cepat dan fleksibel.
</p>
============================================================================================

## Text Generation
<p align="justify">
Text generation menciptakan teks baru berdasarkan input yang diberikan. Dengan menggunakan model yang berbeda, contoh ini menunjukkan kemampuan model untuk menghasilkan kalimat yang relevan dan kreatif, menyoroti fleksibilitas dalam menghasilkan konten.
</p>
============================================================================================

## Fill Mask
<p align="justify">
Fill-mask digunakan untuk memprediksi kata yang hilang dalam sebuah kalimat. Dalam analisis ini, model dapat dengan tepat mengisi kata yang hilang berdasarkan konteks kalimat, menunjukkan pemahaman model terhadap struktur bahasa.
</p>
============================================================================================

## Named Entity Recognition (NER)
<p align="justify">
NER mengidentifikasi dan mengklasifikasikan entitas dalam teks. Contoh ini menunjukkan bagaimana model dapat mengenali nama orang, tempat, dan organisasi dalam kalimat, sangat berguna dalam analisis data teks.
</p>
============================================================================================

## Question Answering
<p align="justify">
Question-answering memungkinkan pengguna untuk mendapatkan jawaban atas pertanyaan berdasarkan konteks yang diberikan. Dua contoh menunjukkan kemampuan model untuk menjawab pertanyaan dengan akurat, mendemonstrasikan penerapan dalam bidang pendidikan dan kesehatan.
</p>
============================================================================================

## Sentiment Analysis
<p align="justify">
Sentiment analysis mengidentifikasi emosi dalam teks, seperti positif, negatif, atau netral. Analisis menunjukkan bagaimana model dapat mengenali dan mengklasifikasikan perasaan dalam kalimat secara otomatis.
</p>
============================================================================================

## Summarization
<p align="justify">
Summarization menghasilkan ringkasan dari teks panjang, menjaga informasi penting. Dalam contoh ini, model berhasil merangkum dampak AI pada berbagai sektor, memberikan pandangan singkat yang berguna.
</p>
============================================================================================

## Translation
<p align="justify">
Translation menerjemahkan teks dari satu bahasa ke bahasa lain. Contoh ini menunjukkan bagaimana model dapat menerjemahkan kalimat dari bahasa Prancis ke bahasa Inggris dengan akurasi yang tinggi.
</p>
============================================================================================

## Cara Menggunakan
1. Clone repositori ini ke komputer Anda.
2. Pastikan Anda memiliki Python dan library Transformers terinstal atau untuk lebih mudahnya bisa gunakan Google Collab.
3. Jalankan skrip di dalam direktori proyek untuk melihat hasil analisis.

