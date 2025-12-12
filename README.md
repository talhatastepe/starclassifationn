# #  NASA Star Type Classification with Machine Learning


##  Proje Hakkında
Bu proje, NASA verilerini kullanarak yıldızların sıcaklık, parlaklık, yarıçap ve renk gibi fiziksel özelliklerine dayanarak türlerini sınıflandırmayı amaçlar. Proje, astronomideki ünlü **Hertzsprung-Russell (H-R) Diyagramı**'nın makine öğrenmesi algoritmaları ile modellenmesi üzerine kuruludur.

##  Veri Seti
Kullanılan veri seti 240 yıldız ve 6 özellikten oluşmaktadır:
- **Temperature (K):** Yüzey sıcaklığı
- **Luminosity (L/Lo):** Parlaklık
- **Radius (R/Ro):** Yarıçap
- **Absolute Magnitude (Mv):** Mutlak Parlaklık
- **Star Color & Spectral Class:** Kategorik özellikler (Label Encoded)

##  Kullanılan Yöntemler
- **Veri Ön İşleme:** Label Encoding, Train-Test Split (%70-%30)
- **Algoritmalar:**
  - `K-Nearest Neighbors (KNN)` (Optimize edilmiş K değeri ile)
  - `Multi-Layer Perceptron (MLP)` (Yapay Sinir Ağları)
  - `Random Forest` (Özellik önem analizi için)
- **Analizler:** 3D Görselleştirme, Çapraz Doğrulama (Cross-Validation), Confusion Matrix.

##  Sonuçlar
| Model | Başarı Oranı (Accuracy) |
|-------|-------------------------|
| KNN   | %100 (Yaklaşık)        |
| MLP   | %100 (Yaklaşık)        |

*Modeller, yıldızların fiziksel kurallara (H-R Diyagramı) sıkı sıkıya bağlı olması nedeniyle yüksek başarı göstermiştir.*

##  Görseller
*(Buraya projedeki H-R diyagramı grafiğinin veya 3D grafiğin ekran görüntüsünü ekleyebilirsin)*

##  Nasıl Çalıştırılır?
1. Repoyu klonlayın.
2. `Stars.csv` dosyasının dizinde olduğundan emin olun.
3. `.ipynb` dosyasını Jupyter Notebook veya Google Colab ile çalıştırın.

---
