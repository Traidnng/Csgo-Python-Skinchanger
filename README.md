Markdown
# 🎭 Csgo-Python-Skinchanger

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg?logo=python&logoColor=white)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Geliştirici: Fiorith](https://img.shields.io/badge/Geli%C5%9Ftiri-Fiorith-brightgreen.svg)](https://github.com/Traidnng)

**Csgo-Python-Skinchanger**, Counter-Strike: Global Offensive (Legacy) bellek mimarisi, kaplama adresleri (addresses) ve istemci içi öğe ID'leri üzerine geliştirilmiş Python tabanlı bir yazılım ve inceleme projesidir.

---

### 🌟 Özellikler

* **Modüler Adres Yapısı:** `addresses.py` üzerinden yönetilen dinamik bellek ve offset tanımlamaları.
* **Kolay Kurulum:** `installer.py` betiği ile gerekli bağımlılıkların otomatik hazırlanması.
* **Özelleştirilebilir Liste:** `skins.txt` dosyası üzerinden okunabilir kaplama ve ID yapılandırması.
* **Hafif Bellek Yönetimi:** `Skinchanger.py` ile optimize edilmiş bellek okuma/yazma süreçleri.

---

### 📂 Proje Yapısı

```text
Csgo-Python-Skinchanger/
├── .gitignore
├── LICENSE
├── README.md
├── Skinchanger.py    # Ana uygulama ve bellek yönetim betiği
├── addresses.py      # Offset ve bellek adres tanımlamaları
├── installer.py      # Bağımlılık ve kurulum betiği
└── skins.txt         # Skin ID ve kaplama listesi
```
🚀 Kurulum & Çalıştırma
Repoyu Klonlayın:

```Bash
git clone [https://github.com/Traidnng/Csgo-Python-Skinchanger.git](https://github.com/Traidnng/Csgo-Python-Skinchanger.git)
cd Csgo-Python-Skinchanger
Gereksinimleri Otomatik Yükleyin:
```

```Bash
python installer.py
Uygulamayı Başlatın:
```


```python Skinchanger.py```
