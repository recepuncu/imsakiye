# 🌙 İmsakiye 2026 - Türkiye İl & İlçe Namaz Vakitleri

Türkiye'deki 81 il ve tüm ilçelere ait 2026 yılı namaz vakitlerini (imsak, güneş, öğle, ikindi, akşam, yatsı) barındıran açık kaynaklı bir projedir. Veriler JSON formatında sunulmakta olup, GitHub Pages üzerinden doğrudan API olarak kullanılabilir.

## 🚀 Canlı Önizleme

Projeyi tarayıcı üzerinden görüntülemek için:
[https://recepuncu.github.io/imsakiye/](https://recepuncu.github.io/imsakiye/)

## 🔗 JSON API Kullanımı

Herhangi bir uygulama veya web sitesinden verileri çekmek için aşağıdaki URL yapısını kullanabilirsiniz:

**URL Yapısı:**
`https://recepuncu.github.io/imsakiye/2026/data/{il}-{ilce}.json`

**Örnekler:**
- **İstanbul:** [https://recepuncu.github.io/imsakiye/2026/data/istanbul-istanbul.json](https://recepuncu.github.io/imsakiye/2026/data/istanbul-istanbul.json)
- **Ankara (Çankaya):** [https://recepuncu.github.io/imsakiye/2026/data/ankara-ankara.json](https://recepuncu.github.io/imsakiye/2026/data/ankara-ankara.json)
- **İzmir (Çeşme):** [https://recepuncu.github.io/imsakiye/2026/data/izmir-cesme.json](https://recepuncu.github.io/imsakiye/2026/data/izmir-cesme.json)

## 📂 Proje Yapısı

```text
imsakiye/
├── 2026/
│   └── data/
│       ├── adana-adana.json
│       ├── istanbul-besiktas.json
│       └── ... (869 ilçe dosyası)
├── index.html      # Kullanıcı arayüzü
├── imsakiye-cover.png
└── README.md
```

## 🛠️ Teknik Özellikler

- **Frontend:** Vanilla JS, HTML5, CSS3.
- **Veri Kaynağı:** Yerel JSON dosyaları.
- **Dil Desteği:** Türkçe (Özel karakter desteği ve doğru büyük harf dönüşümü dahil).
- **Responsive Tasarım:** Mobil, tablet ve masaüstü uyumlu.

## ⚙️ Katkıda Bulunma

1. Bu depoyu forklayın.
2. Yeni bir branch oluşturun (`git checkout -b yeniozellik/Ozellik`).
3. Değişikliklerinizi yapın ve kaydedin.
4. Değişikliklerinizi gönderin (`git commit -m 'Yeni özellik eklendi'`).
5. Branchinize push yapın (`git push origin yeniozellik/Ozellik`).
6. Bir Pull Request açın.

## 📄 Lisans

Bu proje [MIT Lisansı](LICENSE) ile lisanslanmıştır.
