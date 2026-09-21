<img width="724" height="1024" alt="xd" src="https://github.com/user-attachments/assets/f9b22a5c-a725-454a-81d2-6358cbfcf9a1" />
# Decathlon Ürün Yorumlarında Duygu Analizi

Bu proje, lisans bitirme tezim kapsamında Decathlon ürünlerine ait müşteri yorumlarının duygu analizi ve makine öğrenmesi yöntemleriyle incelenmesi amacıyla geliştirildi.

Selenium ile 214 üründen 12.497 müşteri yorumu toplandı. Veri temizleme sonrasında 12.463 Türkçe yorum üzerinde çalışıldı. Yorumlar XLM-RoBERTa tabanlı bir duygu analizi modeli ile pozitif, nötr ve negatif olarak etiketlendi.

Çalışmada 9 farklı makine öğrenmesi algoritması 10-fold stratified cross-validation ile karşılaştırıldı. En yüksek AUC değeri 0.773 ile Gradient Boosting modelinde elde edildi.

SHAP analizi kullanılarak yorum uzunluğu, yıldız puanı, marka, fiyat ve kullanım süresi gibi özelliklerin model tahminleri üzerindeki etkileri incelendi.

## Dataset

- 214 ürün
- 12.497 ham müşteri yorumu
- 12.463 temizlenmiş Türkçe yorum
- 16 spor kategorisi
- 18 marka

## Methods

Selenium · Python · Pandas · NLP · XLM-RoBERTa · Machine Learning · Orange Data Mining · SHAP
