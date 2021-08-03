# Adaline-Algorithm.md
Adaline Algorithm - Artificial Neural Network

Berikut adalah Implementasi Kasus sederhana Jaringan Adaline (Adaptive Linear Neuron) dengan menggunakan Python.

## Metode
+ Inisialisasi semua bobot dan bias (umumnya wi = b =0 )
+ Set laju pembelajaran α (untuk penyederhanaan set α = 0,1)
+ Tentukan toleransi kesalahan yang diijinkan
+ Selama Δwimaxi > batas toleransi, lakukan :
  + Set aktivasi unit masukan xi = si (i = 1, ..., n)
  + Hitung respon unit keluaran: 
    
    y = f(net) = net = Σxiwi + bi
  + Perbaiki bobot pola yang mengandung kesalahan ( y ≠ t ) menurut persamaan

    wi (baru) = wi (lama) + α ( t – y ) xi

    b (baru) = b (lama) + α ( t – y )

## Authors
* **Mega Musfivawati** - *Initial work* - [megamusfiva](https://github.com/megamusfiva/)
