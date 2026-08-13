# BNCC Machine Learning Workshop

Repository ini berisi materi workshop machine learning di 12 Agustus 2026 untuk problem **regression** dan **classification**. Notebook dibuat agar peserta bisa membuat alur machine learning end-to-end.

## Notebook Template

File berikut digunakan sebagai notebook latihan untuk peserta:

- `regression.ipynb`: Template workshop untuk problem house price regression.
- `classification.ipynb`: Template workshop untuk problem sms spam classification.

## Notebook Answer

Folder `answer/` berisi versi lengkap dari notebook template:

- `answer/regression_answer.ipynb`: Jawaban lengkap untuk notebook house price regression.
- `answer/classification_answer.ipynb`: Jawaban lengkap untuk notebook sms spam classification.

## Dataset

Folder `dataset/` berisi dataset yang digunakan:

- `dataset/jakarta_house.csv`: Dataset harga rumah di Jakarta, sumber: https://www.kaggle.com/datasets/abiyyurasyiq/jakarta-house-price-dataset/data
- `dataset/spam.csv`: Dataset SMS spam classification, sumber: https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

## Library yang Dibutuhkan

Library utama yang dibutuhkan:

```bash
pip install pandas matplotlib seaborn scikit-learn
```

Library yang digunakan:

- `pandas`: Untuk membaca dan mengolah dataset.
- `matplotlib` dan `seaborn`: Untuk membuat visualisasi.
- `scikit-learn`: Untuk machine learning.

## Cara Menjalankan

1. Clone atau download repository ini.
```bash
git clone https://github.com/jeremzhg/BNCC-ML-Workshop
```

2. Install library yang dibutuhkan:
```bash
pip install pandas matplotlib seaborn scikit-learn
```

3. Jalankan notebook menggunakan Jupyter Notebook, JupyterLab, VS Code, atau Google Colab.


4. Gunakan file template untuk latihan:
   - `regression.ipynb`
   - `classification.ipynb`

5. Gunakan file di folder `answer/` sebagai referensi jawaban.