# world-bank-economic-development-analysis
An exploratory analysis of global economic, social, and environmental indicators using Python and data visualization.

Bu projede farklı ülkelerin ekonomik, sosyal ve çevresel göstergeleri Python kullanılarak incelenmiştir. Çalışmanın temel amacı veri setini tanımak, değişkenlerin yıllara ve ülkelere göre nasıl değiştiğini görmek ve değişkenler arasındaki ilişkileri görselleştirmektir.

## Çalışmada Neler Var?

Notebook içerisinde;
- veri setinin genel yapısının incelenmesi,
- eksik değer kontrolü,
- GDP, nüfus ve CO₂ emisyonlarının dağılım analizi,
- yıllara göre işsizlik oranlarının karşılaştırılması,
- yaşam beklentisinin ülke ve yıllara göre incelenmesi,
- GDP ve nüfus için heatmap görselleştirmeleri,
- elektriğe erişim oranlarının karşılaştırılması,
- sayısal değişkenler için korelasyon analizi,
- analiz sonunda temel bulguların otomatik olarak özetlenmesi
yer alıyor.

## Veri Seti

Çalışmada Kaggle'da Bhadra Mohit tarafından paylaşılan **World Bank Dataset** kullanılmıştır.
Veri seti, 2010–2019 döneminde 20 ülkeye ait ekonomik, sosyal ve çevresel göstergeleri içeriyor.

> Not: Kaggle açıklamasına göre bu veri seti gerçek Dünya Bankası verilerinin birebir arşivi değil, World Bank göstergelerini örnekleyen/simüle eden bir veri setidir.

**Veri seti:** https://www.kaggle.com/datasets/bhadramohit/world-bank-dataset

## Kullanılan Teknolojiler

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Klasör Yapısı
text
## Klasör Yapısı

```text
world-bank-economic-development-analysis/
│
├── world_bank_dataset.csv
├── world_bank_analysis.ipynb
├── README.md
├── requirements.txt
└── .gitignore


## Çalıştırmak İçin

Projeyi klonladıktan sonra gerekli kütüphaneleri yükleyebilirsiniz:
bash
pip install -r requirements.txt

Ardından notebook'u Jupyter üzerinden açıp çalıştırabilirsiniz.

## Author

**Emine Doğan**  
Data Science & Analytics Student  
Harran University  
GitHub: [profilime buradan ulaşabilirsiniz](https://github.com/emiineedgn)
