# Sentinel Ops · Filo Sağlık Merkezi

Konfigürasyon farkındalıklı, yapay zekâ destekli proaktif bakım ve arıza karar destek sistemi için hazırlanmış ileri seviye frontend mock/demo.

## Çalıştırma

Proje herhangi bir build bağımlılığı olmadan çalışır:

```bash
python3 -m http.server 4173
```

Ardından `http://127.0.0.1:4173` adresini açın.

## Demo kapsamı

- Filo Sağlık Merkezi ve coğrafi risk haritası
- Platform / filo listesi ve platform dijital kartı drawer’ı
- Kritik ekipman listesi ve ekipman sağlık drawer’ı
- AI risk analizi, SHAP benzeri risk faktörleri ve RUL kartları
- Konfigürasyon zaman çizelgesi ve “o tarihe git” slider’ı
- Çevresel maruziyet, akıllı uyarılar ve haftalık bakım planı
- İş emirleri, bakım / arıza günlüğü ve teknik doküman asistanı
- Rogue parça, değişiklik etki, what-if ve yedek parça modülleri
- Analitik / KPI, model sağlığı, veri kalitesi ve rapor merkezi kabukları

## Dosyalar

- `index.html` — uygulama giriş noktası
- `styles.css` — responsive görsel sistem ve bileşen stilleri
- `app.js` — sentetik demo verisi, ekran yönlendirmesi ve etkileşimler

Bu sürüm backend bağlantısı olmadan sentetik veriyle çalışan bir ürün demosudur; servis katmanı bağlandığında aynı ekranlar gerçek API verisiyle beslenebilir.
