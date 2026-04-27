# EV-Selection-MCDM
Hybrid Multi-Criteria Decision Making (MCDM) model for Electric Vehicle selection using MEREC, VIKOR, and MOORA methods. Implemented in Python for performance analysis and visualization.

Elektrikli Araç Seçimi İçin Hibrit ÇKKV Analizi (MEREC-VIKOR-MOORA)
Bu depo, Türkiye pazarındaki elektrikli otomobillerin performans analizi ve sıralanması üzerine yürütülen akademik çalışmanın kaynak kodlarını ve uygulama detaylarını içermektedir.

📝 Hakkında
Bu çalışma, karar verme sürecinde objektif kriter ağırlıklandırma yöntemi olan MEREC ile sıralama yöntemleri olan VIKOR ve MOORA algoritmalarını birleştiren hibrit bir model sunmaktadır. Analiz süreci hem Microsoft Excel üzerinde kurgulanmış hem de Python programlama dili ile doğrulanmış ve görselleştirilmiştir.

🚀 Temel Özellikler
Objektif Ağırlıklandırma: MEREC yöntemi ile kriterlerin "çıkarılma etkisi" üzerinden ağırlık tespiti.

Çok Yöntemli Sıralama: VIKOR (Uzlaşık Çözüm) ve MOORA (Oran Analizi) algoritmalarının entegrasyonu.

Gelişmiş Görselleştirme: Fayda ve maliyet bileşenlerini sıfır ekseni üzerinde gösteren kümülatif performans grafikleri.

Yöntemsel Doğrulama: Python tabanlı çapraz kontrol (cross-check) mekanizması.

📂 Dosya Yapısı
merec_vikor_moora_analysis.py: Tüm analiz adımlarını ve görselleştirme kodlarını içeren ana Python betiği.

ev.xlsx: Analizde kullanılan teknik ve ekonomik verileri içeren karar matrisi (örnek şablon).

görseller/: Analiz sonucunda üretilen grafikler (MEREC Ağırlıkları, Sıralama Değişimi, Performans Dengesi).

🛠️ Kurulum ve Gereksinimler
Kodun çalışması için aşağıdaki Python kütüphanelerinin yüklü olması gerekmektedir:

Bash
pip install pandas numpy matplotlib
📊 Örnek Çıktı
Analiz sonucunda elde edilen kümülatif performans dengesi grafiği, her alternatifin neden o sırada yer aldığını matematiksel olarak görselleştirmektedir.

📚 Atıf (Citation)
Bu çalışmayı veya kodları araştırmalarınızda kullanırsanız lütfen aşağıdaki şekilde atıf yapınız:

Atalay, Ö. (2026). Elektrikli otomobil performans analizi için MEREC tabanlı VIKOR ve MOORA yöntemleri ile hibrit bir yaklaşım. [Yazılım]. GitHub: [Repository Linkiniz]

👤 İletişim
Dr. Öğr. Üyesi Ömer ATALAY Kafkas Üniversitesi, İşletme Bölümü

omeratalay36@gmail.com

<img width="900" height="514" alt="image" src="https://github.com/user-attachments/assets/f1c014cd-8b88-43db-8d09-eba36e089611" />
