# Makine Ogrenmesi - Iris Veri Seti Analizi

Bu proje, Iris cicek veri seti uzerinde temel veri analizi ve gorselleistirme islemlerini icermektedir.

## Icerik

- **MachineLearningExample.ipynb** - Veri analizi ve gorselleistirme adimlari iceren Jupyter Notebook
- **iris.csv** - Iris cicek veri seti (150 ornek, 3 tur)

## Kullanilan Kutuphaneler

- **NumPy** - Sayisal islemler
- **Pandas** - Veri manipulasyonu ve analizi
- **Matplotlib** - Grafik ve gorselleistirme
- **Seaborn** - Istatistiksel gorselleistirme

## Yapilan Islemler

- Veri setinin yuklenmesi ve incelenmesi (`head`, `tail`, `info`, `describe`)
- Eksik veri kontrolu (`isnull`)
- Veri filtreleme ve gruplama
- Gorselleistirme: cizgi grafigi, cubuk grafik, pasta grafigi, sacilim grafigi, pairplot
- Tur bazinda karsilastirmali analiz

## Kurulum

```bash
pip install numpy pandas matplotlib seaborn jupyter
```

## Calistirma

```bash
jupyter notebook MachineLearningExample.ipynb
```
