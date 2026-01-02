# oto_ekspertiz
🚗 AI Botu Destekli Araç Hasar Ön-Değerlendirme Sistemi

Bu proje, kendi geliştirdiğim AI botu ile
araba alım–satımı sürecinde arabadan anlamayan kullanıcılar için
ön hasar değerlendirmesi ve ekspertiz hazırlığı yapmayı amaçlar.

⚠️ Bu sistem kesin ekspertiz değildir.
Profesyonel ekspertiz öncesi karar destek ve farkındalık sağlar.

🎯 Amaç :

Arabadan anlamayan kişilere rehberlik etmek

Ekspertize gitmeden önce doğru soruların sorulmasını sağlamak

Yanlış karar verme riskini azaltmak

🔍 AI Botu Ne Yapıyor?

Araç fotoğraflarını ve kullanıcıdan alınan araç bilgilerini birlikte analiz eder

Olası hasar bölgelerini ve şiddet seviyesini (Low / Medium / High) tahmin eder

Şasi, airbag, taşıyıcı gibi kritik risk bayraklarını işaretler

Profesyonel ekspertiz için kontrol checklist’i üretir

🧠 Teknik Yaklaşım (Özet) :

Multimodal AI botu (fotoğraf + yapılandırılmış araç verisi)

Araç bilgileri vehicle_context JSON formatında modellenir

Hasar türleri, master data olmadan standart etiketlere dönüştürülür

Model çıktısı tamamen JSON formatında alınır (raporlanabilir yapı)

Provider bağımsız mimari (OpenAI SDK üzerinden Gemini entegrasyonu)

🧩 Kullanılan Teknolojiler :

Python

Gradio (UI)

OpenAI SDK (provider-agnostic kullanım)

Google Gemini (ücretsiz model)

Proje tamamen ücretsiz araçlar kullanılarak geliştirilmiştir.


🔐 Kod Paylaşımı Hakkında :

Bu repoda tüm kaynak kodlar paylaşılmamıştır.

Paylaşılan içerik:

Mimari yaklaşım

Akış mantığı

Özet kod yapısı

Amaç, kaç satır kod yazıldığını değil,
gerçek bir probleme nasıl çözüm üretildiğini göstermektir.


⚠️ Sınırlamalar :

Model yalnızca görsel ipuçlarına ve kullanıcı beyanına dayanır

Gizli / iç hasarlar tespit edilemeyebilir

Kesin kararlar için yetkili ekspertiz şarttır
