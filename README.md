# Beach Litter Analytic Dashboard
## 📝 Deskripsi
<p> Beach Litter Analytic Dashboard adalah dashboard interaktif yang dirancang untuk mengidentifikasi dan menganalisis karakteristik sampah yang ditemukan di kawasan pantai. Dashboard ini menyajikan informasi mengenai komposisi material sampah, distribusi jenis sampah, serta potensi daur ulang berdasarkan karakteristik material yang terdeteksi. 
<p> </p>Dengan dashboard ini, pengguna dapat mengetahui jenis material yang paling banyak mencemari pantai dan menilai peluang pemanfaatan kembali dari setiap material sampah yang ditemukan.

## 📂 Analisis
Lihat detail analisis dan visualisasi ini di sini [notebook](https://github.com/nurainazhr/CapstoneDS/blob/main/capstone.ipynb)

## Dataset
Proyek ini menggunakan dataset **Marine Litter Watch: Litter on the Beach** yang tersedia di Kaggle.
Sumber: https://www.kaggle.com/datasets/maartenvandevelde/marine-litter-watch-19502021

## Pertanyaan Bisnis
1. Berapa tingkat daur ulang (_Recycability Rate_) untuk setiap kategori material
2. Berapa rasio sampah yang "Dapat Didaur Ulang" dibandingkan dengan yang "Tidak Dapat Didaur Ulang"?
3. Apa kategori dan jenis sampah yang menyumbang volume sampah non-recyclable terbesar secara global?
4. Bagaimana karakteristik material memengaruhi keberhasilan daur ulang?
5. Bagaimana pola fluktuasi tahunan rata-rata volume sampah plastik di pesisir pantai selama periode 2013–2021? Apakah volume sampah plastik di seluruh pantai terus meningkat dari tahun ke tahun?

## 🔍 Fitur Utama Dashboard
- Analisis Material dan Recyclability: Menganalisis komposisi material dan kelayakan daur ulang sampah di pantai
- Visualisasi Interaktif Komposisi Sampah: Menampilkan distribusi jenis sampah dan material
- Trend Sampah Plastik: Menampilkan total sampah plastik di pantai tahun 2013-2021

## 📊 Dashboard dengan Streamlit
### Streamlit Cloud
Untuk melihat dasbor Streamlit langsung melalui tautan ini: [Dashboard](https://cc26-psu157.streamlit.app/)
#### Preview
<p> Tampilan Beach Litter Analytic Dashboard
  
![3dash](https://github.com/user-attachments/assets/d8e2ee7f-c6e1-4d9c-ada8-357a8b1afcac)

### Run Streamlit on Local
#### Setup Environment - Shell/Terminal
```
mkdir CapstoneDS
cd CapstoneDS
```
#### Install Dependencies
```
pip install -r requirements.txt
```
#### Run Streamlit Dashboard
```
streamlit run dashboard/StreamlitC.py
```
