# KodlaSınav Studio
Soru bankasındaki soruları otomatik olarak kısa sosyal medya videolarına dönüştüren içerik üretim aracı.

KodlaSınav Studio, metin hâlindeki çoktan seçmeli soruları yayına hazır dikey videolara çeviren bir otomasyon uygulamasıdır. Soruyu alır, tasarım şablonuna yerleştirir, cevabı ve açıklamasıyla birlikte MP4 olarak çıkarır.Eğitim içeriği paylaşan biri her soru için tasarımı açmak, metni yerleştirmek, cevap ekranını hazırlamak, videoyu dışa aktarmak ve paylaşım metni yazmak zorundadır. Tek soruda bu kolaydır, yüzlerce soruda ise sürekli tekrarlanan bir işe dönüşür.


Asıl amaç:
Bu tekrarı ortadan kaldırmak. Kullanıcı içeriğin doğruluğuna odaklanır; tasarım, video üretimi ve yayın hazırlığını uygulama yapar. Böylece:
- Yüzlerce soru tek tıkla videoya dönüşür.
- Bütün videolar aynı tasarım dilini taşır.
- Öğrenciler kısa videolarla, kaydırırken tekrar yapabilir.

Nasıl çalışır?
1. Seç: Soru bankasından konu seçilir.
2. Kontrol et: Soru canlı önizlemede incelenir ve düzenlenir.
3. Üret: Sistem soru ve cevap kartlarını çizip videoya çevirir.

Teknik olarak ne içeriyor?
- React + Vite: yönetim paneli ve soru editörü
- Node.js + Express: üretim işlerini yöneten API
- Python + Pillow: metne göre boyutlanan kart çizimi
- FFmpeg: video oluşturma
- Remotion + Edge TTS: seslendirmeli video seçeneği
- Metricool API: yayın planlama
