# 📊 Telekomünikasyon Müşteri Terk (Churn) Analizi Projesi

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Library](https://img.shields.io/badge/Library-Scikit--Learn-orange)
![License](https://img.shields.io/badge/License-MIT-green)

Bu proje, **Veri Analizi** dersi kapsamında bir telekomünikasyon şirketinin müşteri verileri analiz edilerek, hangi müşterilerin hizmeti terk etme (**Churn**) riski taşıdığını tahmin eden bir **Makine Öğrenmesi modeli** geliştirmek amacıyla hazırlanmıştır.

---

##  Proje Sahibi

- **Adı Soyadı:** Mehmet Erdem Karahan  
- **Öğrenci No:** 23430070053  
 

---

##  Proje Özeti

- **Veri Seti:** Telco Customer Churn (Kaggle)  
 
- **Kullanılan Algoritma:** Random Forest Classifier  
 
- **Model Başarısı (Accuracy):** **%78.46**

Bu projede, müşteri davranışlarını etkileyen faktörler analiz edilmiş ve müşteri terkini önceden tahmin edebilen bir model oluşturulmuştur.

---

##  Dosya İçeriği

Bu depo aşağıdaki dosyaları içermektedir:

- **`verianalizi.ipynb`**  
  Veri temizleme, keşifsel veri analizi (EDA), modelleme ve değerlendirme adımlarını içeren Jupyter Notebook dosyası.

- **`makineogrenmesidokumantasyon.pdf`**  
  Projenin metodolojisini, literatür araştırmasını, analiz sonuçlarını ve yorumları içeren akademik rapor.

- **`WA_Fn-UseC_-Telco-Customer-Churn.csv`**  
  Analizde kullanılan orijinal veri seti.

---

##  Önemli Bulgular

Veri analizi ve modelleme sonucunda elde edilen başlıca bulgular şunlardır:

1. **Fiyatlandırma Etkisi**  
   Müşteri terkini etkileyen en önemli değişkenlerin **Aylık Ücret (MonthlyCharges)** ve **Toplam Ödeme (TotalCharges)** olduğu tespit edilmiştir. Yüksek fatura ödeyen müşteriler daha yüksek terk riskine sahiptir.

2. **Müşteri Sadakati (Tenure)**  
   Abonelik süresi kısa olan (yeni) müşterilerin churn oranı, uzun süredir hizmet alan müşterilere kıyasla daha yüksektir.

3. **Sözleşme Tipi**  
   Aylık sözleşmeye sahip müşterilerin terk oranı, 1 yıllık ve 2 yıllık sözleşmeye sahip müşterilere göre belirgin şekilde fazladır.

---

## 🛠️ Kurulum ve Çalıştırma

Projeyi yerel ortamınızda çalıştırmak için aşağıdaki adımları izleyebilirsiniz.

### 1️⃣ Depoyu Klonlayın
```bash
git clone https://github.com/erdemkrhn/musteri-terk-analizi.git
```

### 2️⃣ Gerekli Kütüphaneleri Yükleyin
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 3️⃣ Notebook’u Çalıştırın
```bash
jupyter notebook
```

