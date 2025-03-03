# DSC Fact-Checking -- UIT DSC 2023

Xác thực thông tin (fact-checking) phân loại tuyên bố thành "SUPPORTED", "REFUTED", hoặc "NEI".

## Công nghệ
- **Python**, TensorFlow/Keras, Scikit-learn, Transformers, NumPy, Pandas, NLTK, Sentence Transformers.

## Mô hình
- ANN, DNN, RNN, CNN, Random Forest.
- PhoBERT và Sentence Transformers cho NLP.

## Dữ liệu
- Feature vectors (2048 chiều) từ `.npy`, nhãn từ `.csv`.
- Kết quả xuất JSON (verdict, evidence).

## Cài đặt
```bash
pip install tensorflow keras scikit-learn transformers numpy pandas nltk sentence-transformers joblib
