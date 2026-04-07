# Veriden-Aksiyona-Otomotiv-Sat-Sonras-Hizmetlerde-Stratejik-M-teri-Analizi
Python ile Otomotiv Satış Sonrası Hizmetlerde RFM Analizi ve Stratejik Müşteri Segmentasyonu.

🚗 Veriden Aksiyona: Otomotiv Satış Sonrası Hizmetlerde Stratejik Müşteri Analizi
📌 Proje Özeti
Bu çalışma, otomotiv satış sonrası hizmetler (servis, yedek parça, periyodik bakım) verilerini kullanarak müşteri bağlılığını ve kârlılığını artırmayı hedefleyen analitik bir modeldir. Ham servis verileri RFM (Recency, Monetary) metodolojisi ile işlenerek, her bir müşteri segmenti için özelleştirilmiş aksiyon planları ve stratejik yol haritaları oluşturulmuştur.

🛠️ İş Problemi ve Sektörel Çözüm
Otomotiv dünyasında müşteriyle kurulan bağ, araç anahtarı teslim edildiğinde bitmez; asıl o an başlar. Ancak, binlerce araçlık portföyde hangi müşterinin kaybedilme riski taşıdığını veya hangi grubun sadakat programına dahil edilmesi gerektiğini manuel olarak takip etmek operasyonel bir yüktür.

Çözüm: Geliştirilen bu Python tabanlı algoritma;

    Veri Hijyeni: Kirli, eksik ve hatalı (negatif harcama vb.) servis kayıtlarını ayıklar.

    Analitik Segmentasyon: Müşterileri harcama gücü ve servis ziyaret sıklığına göre segmente eder.

    Proaktif Karar Destek: Pazarlama ve servis operasyonları için reaktif değil, proaktif bir yönetim modeli sunar.

🚀 Analitik İş Akışı
1. Veri Ön İşleme (Data Preprocessing)

    Veri Temizliği: Pandas kullanılarak NaN değerler ve hatalı girişler temizlendi.

    Tarih Dönüşümü: Servis ziyaret tarihleri analiz edilebilir zaman nesnelerine çevrilerek pasif_gun_sayisi hesaplandı.

    Sektörel Uyumluluk: Veri seti; araç segmenti, servis harcaması ve ziyaret sıklığı gibi otomotiv dinamiklerine göre yapılandırıldı.

2. Segmentasyon Mantığı (RFM Logic)

Algoritma, müşterileri 4 ana stratejik gruba ayırır:

    💎 VIP (Yüksek Değer & Aktif): Düzenli servis ziyareti yapan ve yüksek bütçeli bakım harcaması olan kitle.

    ⭐ Sadık (Geri Kazanılmalı): Geçmişte yüksek değer üretmiş ancak servis periyodu gecikmiş müşteriler.

    🌱 Potansiyel (Yeni/Aktif): Yeni araç almış veya ilk servisini yapmış, sadakat programına aday grup.

    🚨 Risk (Kaybedilme Olasılığı): Hem harcama tutarı düşük hem de servis ziyaretleri arasındaki süre çok uzamış kitle.

📊 Görsel Raporlama ve Stratejik Çıktılar
![Otomotiv Satış Sonrası Hizmetlerde Stratejik Müşteri Analizi  1](https://github.com/user-attachments/assets/0178f054-c256-4635-b235-08d6e91684c2)


Proje, teknik veriyi bir "Yönetici Özeti"ne dönüştürür. Üretilen "Otomotiv Müşteri Portföyü Dağılımı" raporu, işletmenin mevcut durumunu net bir şekilde ortaya koyar.

    📍 Stratejik Not:
    Analiz sonucunda portföyün %20'sinin Risk, %40'ının Potansiyel ve %40'ının VIP/Sadık olduğu saptanmıştır. Bu veriler ışığında, kaynakların %40'lık potansiyel grubu sadık hale getirmek için kullanılması ve risk grubuna "geri kazanım" odaklı yaklaşılması önerilmektedir.

💻 Kullanılan Teknolojiler

    Python: Ana geliştirme dili.

    Pandas: Veri temizleme, manipülasyon ve analitik hesaplamalar.

    Matplotlib: Sektörel raporlama görselleri.

    Io & Datetime: Veri akışı ve zaman yönetimi.

📂 Dosya Yapısı

    otomotiv_segmentasyon.py: Ana analiz ve görselleştirme kodu.

    otomotiv_segmentasyon_analizi.png: Segmentasyon dağılım grafiği (Dashboard).

    otomotiv_stratejik_analiz_raporu.csv: Atanmış segmentleri içeren detaylı müşteri listesi.
    
Geliştiren: Mercan Köseoğlu
Data Analyst & SAP ABAP Consultant
