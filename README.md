Ali Sait Öz 2021556050 2.öğretim 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AliSaitoz/agenttt/blob/main/colab.ipynb)
# ⚖️ Türk İş Hukuku Bilirkişi Raporu Asistanı (AI Agent)

Bu proje, **Türk İş Hukuku** alanındaki bilirkişi raporlarını analiz etmek, emsal raporlardan öğrenmek ve **RAG (Retrieval-Augmented Generation)** tekniği kullanarak yeni rapor taslakları oluşturmak amacıyla geliştirilmiş bir yapay zeka asistanıdır.

Proje **Google Colab** üzerinde geliştirilmiştir ve PDF formatındaki geçmiş raporları işleyerek hukuki bağlama uygun içerik üretir.

## 🚀 Proje Hakkında

İş hukuku davalarında bilirkişi raporları, teknik hesaplamalar (kıdem tazminatı, ihbar tazminatı vb.) ve hukuki değerlendirmeler içeren karmaşık belgelerdir. Bu proje şu problemleri çözmeyi hedefler:

* **Otomatik Analiz:** PDF formatındaki geçmiş bilirkişi raporlarını okur ve yapılandırılmamış veriyi işler.
* **Bağlamsal Öğrenme (RAG):** Vektör veritabanı kullanarak benzer vaka örneklerini ve ilgili hukuk maddelerini tespit eder.
* **Rapor Üretimi:** Verilen yeni vaka verilerine dayanarak, standartlara uygun ve hukuki dili doğru kullanan taslak raporlar oluşturur.

## 🛠️ Kullanılan Teknolojiler

* **Platform:** Google Colab (GPU Hızlandırma ile)
* **Dil:** Python
* **Yöntem:** RAG (Retrieval-Augmented Generation) & LLM Fine-Tuning
* **Veri İşleme:** PDF Parsing (PyPDF / LangChain vb.)
* **Model:** *[Buraya kullandığın modeli yazabilirsin, örn: Mistral-7B, Llama-3, vb.]*

## 📂 Kurulum ve Kullanım

Bu proje Google Colab üzerinde çalıştırılmak üzere tasarlanmıştır.

1.  `.ipynb` uzantılı proje dosyasını Google Colab'de açın.
2.  Çalışma zamanı türünü **GPU** (T4 veya A100) olarak seçtiğinizden emin olun.
3.  Gerekli kütüphaneleri yüklemek için ilk hücreyi çalıştırın:
    ```python
    !pip install -r requirements.txt
    ```
4.  Eğitim veya referans verisi olarak kullanılacak PDF dosyalarınızı Colab'in dosya dizinine yükleyin.

## ⚠️ Yasal Uyarı

Bu proje **eğitim ve deneysel amaçlarla** geliştirilmiştir. Üretilen raporlar, resmi hukuki tavsiye veya nihai bilirkişi raporu niteliği taşımaz. Çıktılar mutlaka yetkili bir bilirkişi veya hukuk uzmanı tarafından kontrol edilmelidir.

## 📝 Lisans
