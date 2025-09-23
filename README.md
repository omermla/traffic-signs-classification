
# Trafik İşaretleri Sınıflandırma Projesi

## Proje Özeti
Bu proje, Akbank Derin Öğrenme Bootcamp kapsamında geliştirilmiştir. Trafik İşaretleri veri seti kullanılarak 43 farklı trafik işaretini sınıflandırmak için bir CNN modeli oluşturulmuştur.

## Adımlar
1. **Veri Ön İşleme**: Veri seti yüklendi, normalleştirildi, veri çoğaltma uygulandı.
2. **Model Geliştirme**: CNN modeli oluşturuldu ve eğitildi (%94.86 test doğruluğu).
3. **Değerlendirme**: Test setinde doğruluk/kayıp, karışıklık matrisi ve sınıflandırma raporu üretildi.
4. **Grad-CAM**: Modelin odaklandığı bölgeler görselleştirildi.
5. **Hiperparametre Optimizasyonu**: Keras Tuner ile model iyileştirildi (Test doğruluğu: %91.48).

## Sonuçlar
- İlk Model Test Doğruluğu: %94.86
- En İyi Model Test Doğruluğu: %91.48
- Veri Seti: 34799 eğitim, 4410 doğrulama, 12630 test örneği
- Sınıf Sayısı: 43
- Görüntü Boyutu: 32x32x3

## Kullanılan Kütüphaneler
- TensorFlow, Keras, Keras Tuner, tf-keras-vis
- NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn

## Kurulum
```bash
pip install tensorflow keras-tuner tf-keras-vis numpy pandas matplotlib seaborn scikit-learn
```

## Kaggle Notebook
https://www.kaggle.com/code/merfarukmila/trafik-aretleri-s-n-fland-rma
## Lisans
MIT License
