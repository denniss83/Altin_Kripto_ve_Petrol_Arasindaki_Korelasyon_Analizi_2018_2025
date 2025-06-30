# 📊 Altın, Kripto ve Petrol Korelasyon Analizi (2018–2025)

---

## ⚠️ Uyarı

>❗️ **Bu çalışma, Python programlama dili kullanılarak yalnızca veri analizi becerilerini geliştirmek amacıyla hazırlanmıştır.**  
>**Gerçek yatırım tavsiyesi içermez. Hiçbir ticari amaç taşımamaktadır.**

Bu projede; dijital varlıklar (Bitcoin ve Ethereum), geleneksel güvenli liman (Altın) ve enerji piyasasının göstergesi olan Ham Petrol'ün (WTI) fiyat hareketleri ve aralarındaki ilişkiler incelenmiştir.  
Amaç, bu 4 varlığın 2018–2025 yılları arasındaki getirilerini karşılaştırmak ve korelasyon yapılarını zaman içinde analiz etmektir.

---

## 📌 Proje İçeriği

- Normalize fiyat karşılaştırması (2018 = 100 bazlı)
- Günlük ve kümülatif getiri analizleri
- Korelasyon matrisi (heatmap)
- Rolling korelasyon analizi (90 günlük pencere ile)
- BTC–ETH–Altın–Petrol ilişkilerinin yorumlanması

---

## 🛠️ Kullanılan Teknolojiler

- Python
- pandas, numpy, matplotlib, seaborn
- yfinance

---

## 📥 Veri Kaynağı

Veriler `yfinance` kütüphanesi aracılığıyla [Yahoo Finance](https://finance.yahoo.com/) üzerinden alınmıştır:

| Varlık  | Sembol     | Açıklama                      |
|---------|------------|-------------------------------|
| BTC     | BTC-USD    | Bitcoin (USD bazında)         |
| ETH     | ETH-USD    | Ethereum (USD bazında)        |
| Altın   | GLD        | SPDR Gold Shares ETF (Altın)  |
| Petrol  | CL=F       | WTI Ham Petrol (Vadeli)       |
| Tarih   | 2018–2025  | Günlük kapanış fiyatları      |

---

## 📈 Sonuç ve Bulgular

- En yüksek getiri genellikle BTC ve ETH tarafından sağlanmıştır.
- Altın, istikrarlı ama düşük riskli performans göstermiştir.
- BTC ve ETH arasında güçlü pozitif korelasyon vardır (ρ ≈ 0.80+).
- Altın ve Petrol ile olan korelasyonlar zayıf–orta düzeyde ve dönemsel değişkendir.
- Rolling korelasyon analizleri, kriz dönemlerinde geçici yakınsama göstermiştir.


---

## 👤 Hazırlayan

**Deniz Atabey**  
