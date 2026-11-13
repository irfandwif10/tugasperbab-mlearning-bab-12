# tugasperbab-mlearning-bab-12
## 12. Praktikum Bab 12: Neural Network (MLP) & Early Stopping

### 1. Eksperimen Arsitektur MLP (Praktikum 1):
- **Hidden Layers & Neuron:** Penambahan jumlah lapisan tersembunyi (*hidden layers*) dan neuron mampu meningkatkan kapasitas model dalam mempelajari pola data yang kompleks.
- **Hasil:** Arsitektur yang terlalu kecil berisiko *underfitting*, sedangkan arsitektur yang terlalu besar memerlukan waktu latih lebih lama dan rentan terhadap *overfitting*.

### 2. Early Stopping (Praktikum 2):
- **Fungsi:** Menghentikan proses pelatihan secara otomatis ketika performa validasi (*val_loss*) tidak lagi menunjukkan peningkatan selama beberapa epoch tertentu (`patience`).
- **Keunggulan:** Efektif mencegah *overfitting* sekaligus menghemat waktu komputasi dengan mengembalikan bobot model terbaik secara otomatis (`restore_best_weights=True`).
