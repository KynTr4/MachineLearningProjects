# GitHub README Yazısı (Kişisel Makine Öğrenmesi Projeleri)

# Makine Öğrenmesi Projelerim

Bu depo, Kaggle'daki popüler veri setleri üzerinde geliştirdiğim kişisel makine öğrenmesi projelerini içermektedir.

## Projeler

### 1. Advanced Regression Techniques (Ev Fiyat Tahmini)
- **Veri Seti**: [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/h...)
- **Amaç**: Konut özelliklerine göre ev fiyatlarını tahmin etmek
- **Uygulanan Teknikler**:
  - Kapsamlı veri analizi ve özellik mühendisliği
  - Çoklu regresyon modellerinin karşılaştırılması
  - Model stacking ve ensemble yöntemleri
- **Başarı Metrikleri**: RMSE = 0.12, R² = 0.91
- **Dosyalar**: `data_exploration.ipynb`, `feature_engineering.py`, `final_model.ipynb`

### 2. Titanic Hayatta Kalma Tahmini
- **Veri Seti**: [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/t...)
- **Amaç**: Yolcu özelliklerine göre hayatta kalma tahmini yapmak
- **Öne Çıkanlar**:
  - Eksik veri analizi ve doldurma yöntemleri
  - Sınıflandırma algoritmalarının performans karşılaştırması
  - Özellik ölçeklendirme ve seçme teknikleri
- **Doğruluk**: %82.3 (Cross-Validation)
- **Dosyalar**: `titanic_analysis.ipynb`, `preprocessing_functions.py`

### 3. Spaceship Titanic (Uzay Yolcu Tahmini)
- **Veri Seti**: [Spaceship Titanic](https://www.kaggle.com/competitions/s...)
- **Amaç**: Uzay yolcularının taşınma durumunun tahmin edilmesi
- **Yenilikçi Yaklaşımlar**:
  - Kategorik veriler için özel encoding teknikleri
  - Dengesiz veri seti için örnekleme yöntemleri
  - Neural Network tabanlı sınıflandırıcı
- **Doğruluk**: %79.1
- **Dosyalar**: `spaceship_preprocessing.ipynb`, `nn_model.py`


## Teknoloji Yığını

- Python 3.9+
- Scikit-learn
- Pandas/Numpy
- Matplotlib/Seaborn
- TensorFlow (Spaceship projesi için)


## Lisans

Bu proje MIT lisansı altında lisanslanmıştır - detaylar için [LICENSE.md](https://github.com/KynTr4/MachineLearningProjects/blob/main/LICENSE) dosyasına bakınız.
