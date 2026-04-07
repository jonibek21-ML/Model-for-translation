# Sentiment-Analysis-Model
# Multilingual Sentiment Analysis (IMDB Dataset)

## 📌 Loyiha haqida

Ushbu loyiha **tabularisai/multilingual-sentiment-analysis** modelidan foydalanib **IMDB movie reviews dataset** asosida sentiment (ijobiy / salbiy) klassifikatsiya qilishni ko‘rsatadi.

Loyiha maqsadi — Hugging Face Transformers yordamida oddiy va tushunarli **NLP pipeline** qurish.

---

## 📂 Dataset

Dataset: **IMDB Movie Reviews**

Xususiyatlari:

* 50,000 ta review
* 2 ta klass: Positive / Negative
* Train: 25,000
* Test: 25,000

Label qiymatlari:

* 0 → Negative
* 1 → Positive

Dataset yuklash:

```
load_dataset("imdb")
```

---

## 🧠 Model

Foydalanilgan model:

```
tabularisai/multilingual-sentiment-analysis
```

Model imkoniyatlari:

* Ko‘p tillarni qo‘llab-quvvatlaydi
* Transformer arxitekturasi asosida
* Sentiment classification uchun tayyor
* Hugging Face Trainer bilan oson ishlaydi

---

## ⚙️ Kutubxonalar

Kerakli kutubxonalar:

```
transformers

datasets

torch

scikit-learn
```

O‘rnatish:

```
pip install transformers datasets torch scikit-learn
```

---

## 🔄 Pipeline bosqichlari

Loyiha quyidagi bosqichlardan iborat:

1. Dataset yuklash
2. Tokenization qilish
3. Modelni yuklash
4. Training
5. Evaluation
6. Prediction

---

## 📊 Training parametrlari (example)

```
learning_rate = 2e-5
batch_size = 8 yoki 16
num_train_epochs = 3
```

GPU mavjud bo‘lsa natija yanada yaxshi bo‘ladi.

---

## 📈 Baholash (Evaluation)

Asosiy metric:

```
Accuracy
```

Qo‘shimcha metriclar:

```
Precision
Recall
F1-score
```

---

## 🎯 Loyiha orqali o‘rganiladi

Ushbu loyiha orqali:

* Transformer bilan ishlash
* Tokenization jarayoni
* Hugging Face Trainer ishlatish
* Sentiment classification pipeline

kabi ko‘nikmalar hosil qilinadi.

---

## ⭐ Xulosa

Bu loyiha NLP boshlovchilar uchun sentiment classification pipeline’ni amaliy tarzda tushunishga yordam beradi.
