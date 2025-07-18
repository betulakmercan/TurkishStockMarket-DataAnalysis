Borsa Hisse Analizi ve Tahmin Platformu
Bu proje, Borsa İstanbul’da işlem gören seçili hisselerin (THYAO, GARAN, AKBNK, TUPRS) geçmiş fiyat ve hacim verilerini analiz eder.                                                                                            
Exponential Smoothing yöntemiyle ileriye dönük tahminler üretir ve sonuçları karşılaştırmalı olarak sunar.

🚀 Proje Özeti     
Veri Analizi: Hisselerin geçmiş fiyat (OPEN, HIGH, LOW, CLOSE) ve hacim (VOLUME) verileri detaylı şekilde incelenir.                         
Tahminleme: Exponential Smoothing ile 2025 Ağustos sonrası için fiyat ve hacim tahminleri yapılır.             
Karşılaştırmalı Sonuçlar: Tüm hisselerin geçmiş ve tahmini performansları tablo ve grafiklerle karşılaştırılır.
Görselleştirme: Her hisse için iki ayrı grafik (fiyatlar ve hacim) oluşturulur, mevcut ve tahmini değerler canlı renklerle gösterilir.

🛠️ Kullanılan Teknolojiler     
Python 3.x    
pandas   
numpy   
matplotlib  
statsmodels (Exponential Smoothing)

📊 Analiz Akışı               
CSV formatında hisse verileri projeye eklenir ve veriler yüklenir.
Veriler pandas ile okunur, tarih ve sayısal dönüşümler yapılır.
Her hisse için geçmiş veriler analiz edilir.
Exponential Smoothing ile 2025 Ağustos - 2026 sonu için tahminler üretilir.
Fiyatlar (OPEN, HIGH, LOW, CLOSE) ve Hacim (VOLUME) ve tahmini yapılır.
Tüm hisselerin geçmiş ve tahmini performansları karşılaştırılır.
Hangi hissenin daha istikrarlı, hangisinin daha volatil olduğu, tahmin edilen trendler ve olası yatırım fırsatları analiz edilir.

📈 Sonuçlar ve Karşılaştırma     
THYAO ve TUPRS, hem geçmişte hem de tahminlerde en yüksek fiyat artışı potansiyeline sahip hisseler olarak öne çıkıyor.
GARAN ve AKBNK, daha istikrarlı ve düşük volatiliteye sahip.
TUPRS ve THYAO’da fiyat dalgalanmaları (volatilite) daha yüksek.
Hacim açısından GARAN en yüksek ortalamaya sahip, TUPRS ise en düşük hacimli hisse.
Tahminler, geçmiş trendlerin devam edeceğini varsaymakta olup, gerçek piyasa koşullarında sapmalar olabilir.
