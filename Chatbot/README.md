
# Chatbot dengan Flask

Ada 2 cara untuk menjalankan aplikasi Chatbot ini pada local direktori anda

1. Jalankan Langsung
2. Jalankan dengan Custom Data


## 1. Jalankan Langsung
Setelah anda download semua file folder ini pastikan anda sudah menginstall library pada environment anda :
- tensorflow 
- keras 
- pickle
- nltk
- flask
- numpy

masuk ke dalam path folder Chatbot dan jalankan perintah "python app.py"

## 2. Jalankan dengan Custom Data
1. Buatlah data baru dan masukkan masukkan ke dalam data.json sesuai dengan format sebelumnya
2. hapus file labels.pkl, texts.pkl, model.h5 yang ada pada folder ini
3. jalankan file training.py untuk mendapatkan labels.pkl, texts.pkl, model.h5 yang baru (jika terkendala anda juga dapat menggunakan bantuan google colab untuk mendapatkan 3 file tersebut)
4. jalankan file app.py dengan perintah "python app.py"
