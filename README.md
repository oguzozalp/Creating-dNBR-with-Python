# 🌲 Karabük Orman Yangınını Takip Etmek - dNBR Analizi

Bu repo, Python kullanarak **dNBR (Differenced Normalized Burn Ratio)** hesaplamalarını ve görselleştirmelerini içerir. Karabük’teki orman yangını öncesi ve sonrası Sentinel-2 uydu verileri kullanılarak analiz yapılmıştır.

---

## 📂 İçerik

- `dNBR_testing.ipynb` - Jupyter Notebook ile tüm analiz adımları  
- `dNBR_testing.py` - Python scripti olarak aynı analiz  
- `.gitignore` - Git için dosya hariç tutma ayarları  
- `.gitattributes` - Dosya ayarları  

> Not: Sentinel-2 uydu görüntüleri dosya boyutu nedeniyle GitHub’da paylaşılmamıştır. Burada Copernicus Browser üzerinden kendi elde edeceğiniz görüntüleri kullanabilirsiniz.

---

## 📈 dNBR Analizi

- **dNBR nedir?**  
  Yangın öncesi ve sonrası NBR farkını alarak yangının etkisini göstermek için kullanılan bir endekstir.  

- **Kullanım:**  
  Python kodu ile dNBR hesaplanır, belirlenen alan üzerinde histogram ve görsel üretilebilir.  

  

---

## 🛠️ Kullanım

1. Repoyu klonlayın:  
   ```bash
   git clone https://github.com/oguzozalp/Creating-dNBR-with-Python.git
