---
baslik: "LLM'leri Nasıl Kullanıyorum? (Andrej Karpathy)"
bolum: ai
etiketler: [llm, chatgpt, claude, prompt, araclar]
video: https://www.youtube.com/watch?v=EWvNQjAaOHw
sure: "~2 sa 11 dk"
kaynak_reel: "AI bölümünün temel videosu (kullanıcı seçimi)"
durum: izlenecek
dogrulama: "Transkriptten doğrulanmadı: bilinen içerik ve arama özetlerinden yazıldı."
---

# LLM'leri Nasıl Kullanıyorum? (Andrej Karpathy)

## 1. Kısa özet
OpenAI'ın kurucu ekibinden ve Tesla'nın eski yapay zeka direktörü Andrej Karpathy, LLM'leri günlük hayatta nasıl kullandığını teknik olmayan bir dille gösteriyor. Video, bir LLM'in aslında ne olduğunu anlatarak başlıyor: interneti sıkıştıran ve belli bir tarihe kadar olanları bilen bir "zip dosyası". Ardından düşünen modeller, internet araması, derin araştırma, dosya yükleme, kod çalıştırma, ses ve görsel gibi araçları tek tek gösteriyor. Ana mesaj şu: hangi işte hangi modeli ve hangi aracı kullanacağını bilirsen LLM'den çok daha fazla verim alırsın.

## 2. Ana kavramlar
- **Token:** Modelin metni okuduğu küçük parçalar. Model kelimeleri değil token'ları görür.
- **Bağlam penceresi (context window):** Modelin "çalışma belleği". Sohbet uzadıkça dolar ve model eski kısımlara daha az odaklanır.
- **Bilgi kesim tarihi (knowledge cutoff):** Model eğitildiği tarihten sonrasını kendi başına bilmez. Güncel bilgi için arama aracı gerekir.
- **Ön eğitim / son eğitim:** Önce internetten genel bilgi öğrenilir (ön eğitim), sonra asistan gibi davranması öğretilir (son eğitim).
- **Düşünen modeller (thinking / reasoning):** Pekiştirmeli öğrenmeyle eğitilmiş modeller. Cevap vermeden önce "düşünürler". Matematik, kod ve zor problemlerde daha iyidirler ama daha yavaştırlar.
- **Araç kullanımı (tool use):** İnternet araması, derin araştırma (deep research), kod çalıştırıcı (Python), dosya okuma.
- **Artifacts / uygulama ürettirme:** Claude gibi modellerin küçük uygulamalar, diyagramlar ve oyunlar yazıp tarayıcıda çalıştırması.
- **Ses ve görsel:** Sesli sohbet, görsel yükleyip soru sorma, görsel üretme, NotebookLM ile bir belgeden "podcast" oluşturma.
- **Hafıza ve özel talimatlar:** Modelin seni tanıması için kalıcı notlar, custom instructions ve özel GPT'ler.
- **LLM Konseyi:** Önemli bir kararda aynı soruyu birden fazla modele (ChatGPT, Claude, Gemini…) sorup cevapları karşılaştırmak.

## 3. Nasıl uygulanır
1. **Konu değişince yeni sohbet aç.** Bağlam penceresini temiz tut; alakasız eski mesajlar modelin dikkatini dağıtır.
2. **İşe göre model seç:** Hızlı sorulara normal model. Kod, matematik ve plan gibi zor işlere düşünen model.
3. **Güncel bir şey soruyorsan aramayı aç.** Model kesim tarihinden sonrasını bilmez, tahmin eder.
4. **Bir konuyu derinlemesine öğrenmek için:** Kitap bölümünü ya da makaleyi yükle, "bunu bana adım adım anlat, sonra beni test et" de.
5. **Sayılar ve hesap için** modelden kafadan hesap yapmasını isteme. "Python ile hesapla" de.
6. **Önemli kararlar için LLM Konseyi:** Aynı promptu 2-3 modele sor, farklı cevapları karşılaştır.
7. **Özel talimat yaz:** Kim olduğunu, neyi öğrendiğini ve nasıl cevap istediğini (Türkçe, kısa, örnekli…) bir kere yaz, her sohbette tekrar etme.
8. **Uygulama ve oyun yaptır:** "Bana … yapan basit bir web uygulaması yaz" de, artifact olarak çalıştır, sonra küçük adımlarla değiştirt.

## Bağlantılı konular
- Karpathy, "Deep Dive into LLMs like ChatGPT": LLM'lerin içini daha ayrıntılı anlatan önceki video.
- Prompt yazma (Anthropic "Prompting 101"): eklenecek.
