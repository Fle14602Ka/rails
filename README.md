# üzüm-tanima

Proyek computer vision untuk mengenali tandan anggur, bagian yang memar, tangkai, dan daun memakai model YOLOv8. Bobot dilatih pada kumpulan gambar yang dikumpulkan dan dianotasi sendiri, lalu disetel berulang sampai akurasinya masuk akal. Langkah berikutnya kemungkinan menambah jumlah gambar dan menyetel arsitekturnya lebih jauh.

## Isi repositori

- `testCanli.py` — mengambil gambar langsung dari kamera dan menggambar hasil deteksi di setiap bingkai.
- `testKoordinat.py` — hanya menandai satu kelas (dalam hal ini tandan anggur) lalu mencetak koordinatnya di layar.
- `testMerkezNokta.py` — menggambar kotak dan titik pusat pada gambar diam sebagai contoh keluaran deteksi.

## Memasang

### Yang dibutuhkan

- Python 3.x
- pustaka OpenCV
- pustaka YOLO dari Ultralytics

Pasang keduanya lewat pip:

```
python -m pip install opencv-python-headless ultralytics
```

Contoh keluaran

<img src="https://cdn.example.dev/shots/grape-example.png" alt="Contoh" style="width:600px;height:800px;">