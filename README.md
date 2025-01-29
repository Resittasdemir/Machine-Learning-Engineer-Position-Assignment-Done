# Tesla Hisse Senedi Analizi

## Proje Açıklaması
Bu proje, Tesla hisse senedi verilerini analiz etmek ve kapanış fiyatlarını tahmin etmek için makine öğrenmesi tekniklerini kullanmaktadır.

## Kullanılan Kütüphaneler
- pandas      2.2.2
- numpy       1.26.4
- matplotlib  3.8.4
- seaborn     0.13.2


## Çalıştırma Talimatları
1. Gerekli bağımlılıkları yükleyin:
   ```bash
   pip install pandas numpy matplotlib seaborn 
   ```
2. `Tesla.csv` dosyanızın proje dizininde bulunduğundan emin olun.
3. Python betiğini çalıştırın:
   ```bash
   python Tesla.ipynb
   ```

## İçerik
- `Tesla.ipynb`: Veri ön işleme, teknik göstergeler ve modelleme betiği.
- `README.md`: Kurulum ve çalıştırma talimatları.
- `Tesla Hisse Senedi Analizi.pdf`: Analiz raporu.

## Değerlendirme Metrikleri
- Ortalama Karesel Hata (MSE)
- R² Skoru

## Sonuçlar ve Gelecek Geliştirmeler
Model doğrusal regresyon temelinde çalışmaktadır. Daha gelişmiş tahminler için LSTM gibi derin öğrenme modelleri değerlendirilebilir.