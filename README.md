# EmotionSentimentLLMFineTune

Tento repozitár obsahuje experimenty s doladením veľkých jazykových modelov (LLM) na úlohy analýzy sentimentu a detekcie emócií, najmä v kontexte finančných textov.

## 📁 Štruktúra projektu

```
EmotionSentimentLLMFineTune/
├── data/
│   └── [dátové súbory použité pri hodnotení modelov]
├── DistilBERT_FinanceSentimentDataset.ipynb
├── DistilBERT_StockEmotions.ipynb
├── FinBERT_StockEmotions.ipynb
├── ISEAR_FineTunning/
│   └── [notebooky pre doladenie modelov RoBERTa, BERT, DistilBERT, DistilRoBERTa na ISEAR datasete]
├── KDfromRobertaToDistilRoBERTa.ipynb
└── README.md
```



### 📄 Popis súborov

* `data/` – dátové súbory použité pri hodnotení modelov.
* `DistilBERT_FinanceSentimentDataset.ipynb` – doladenie modelu DistilBERT na finančný sentimentový dataset.
* `DistilBERT_StockEmotions.ipynb` – doladenie DistilBERT na detekciu emócií v finančných textoch.
* `FinBERT_StockEmotions.ipynb` – využitie FinBERT na klasifikáciu emócií v kontexte akciového trhu.
* `ISEAR_FineTunning/` – priečinok obsahujúci notebooky pre doladenie modelov na ISEAR datasete.
* `KDfromRobertaToDistilRoBERTa.ipynb` – aplikácia znalostnej destilácie z modelu RoBERTa do DistilRoBERTa.
* `README.md` –  súbor s popisom projektu.

## 🧪 Použité modely

* **DistilBERT** – odľahčená verzia BERT-u vhodná pre rýchlejšie trénovanie.
* **FinBERT** – BERT model predtrénovaný na finančných textoch, optimalizovaný pre analýzu sentimentu a emócií v oblasti financií.
* **RoBERTa** a **DistilRoBERTa** – modely využité v procese znalostnej destilácie pre analýzu sentimentu a emócií v oblasti financií.


## 📊 Dátové sady

* **ISEAR** –  súbor pre výskum emócií, obsahujúci anotované emocionálne reakcie.
* **Finančné texty** – vlastné alebo verejne dostupné dátové sady z oblasti financií a akciového trhu.


## 📌 Poznámky

* Notebooky sú navrhnuté tak, aby boli spustiteľné v prostredí ako Google Colab alebo Jupyter Notebook.


