#### Proje: World Happiness Report Analizi

Bu proje, **World Happiness Report** verilerinin incelenmesini ve analiz edilmesini içerir. Farklı yıllara ait mutluluk verileri, GDP, sosyal destek, özgürlük gibi parametrelerle detaylı analiz edilmiş ve çeşitli görselleştirmeler yapılmıştır.

---

### İçerik

#### 1. Kullanılan Kütüphaneler
- **Veri Analizi**: `pandas`, `numpy`
- **Görselleştirme**: `matplotlib`, `seaborn`, `plotly`
- **Uyarı Yönetimi**: `warnings`

#### 2. Veriler
- **Veri Setleri**:
  - `world-happiness-report.csv`
  - `world-happiness-report-2021.csv`
  - `population_total_long.csv`
- **Kolonlar**: `Country name`, `Ladder score`, `Social support`, `Freedom to make life choices`, `Generosity`, vb.

#### 3. Veri İşleme ve Analiz Adımları
- Veri keşfi: `data.info()`, `data.describe()`, sütun ve benzersiz değerlerin analizi.
- Görselleştirmeler:
  - Bölgesel mutluluk dağılımları (örneğin: `sns.boxplot` ile).
  - Zaman serileri: Plotly kullanılarak dinamik görseller.
  - Korelasyon matrisi analizi.
- Veri temizleme ve filtreleme:
  - Eksik ya da uyumsuz verilerin çıkarılması.
  - Spesifik yıllar ve bölgeler üzerine odaklanma.

#### 4. Görselleştirme
- **Boxplot**: Değişkenlerin dağılımlarını gösterir.
- **Choropleth Map**: Bölgesel analizler.
- **Scatter Plot**: Özgürlük ve GDP gibi değişkenlerin mutluluk skoru ile ilişkisi.

#### 5. Kodlar
- Veri yükleme ve keşif kodları.
- Farklı analizler ve görselleştirme teknikleri.
- Zamanla değişen mutluluk göstergelerini anlamak için etkileşimli grafikler.

---

# Kurulum

1. Gerekli kütüphaneleri yükleyin:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly
   ```
2. Gerekli veri setlerini temin edin ve proje dizinine yerleştirin.
3. `happiness_world.ipynb` dosyasını çalıştırarak analizleri inceleyin.


### Çıktılar
- Dünyanın en mutlu ve en mutsuz bölgeleri.
- GDP ve sosyal faktörlerin mutluluk üzerindeki etkileri.
- Bölgesel mutluluk farklılıkları.


Detaylı bilgi için Jupyter Notebook'u inceleyebilirsiniz.
