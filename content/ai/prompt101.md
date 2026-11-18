---
baslik: "Prompting 101"
bolum: ai
kaynak: "ANTHROPIC"
sure: "~24 DK"
video: "https://www.youtube.com/watch?v=ysPbXH0LpIE"
video_dogrulandi: "arama sonucundan"
dogrulama: "Transkriptten doğrulanmadı."
---

# Prompting 101

## 1. Kısa özet
Anthropic'in uygulamalı yapay zeka ekibi, gerçek bir örnek üzerinden iyi bir prompt'u adım adım kuruyor: bir sigorta hasar formunu ve kaza çizimini Claude'a analiz ettirmek. İlk prompt kötü sonuç veriyor; görev bağlamı, arka plan bilgisi, net talimatlar, örnekler ve çıktı biçimi eklendikçe sonuç düzeliyor. Ana mesaj: prompt yazmak deneyerek ilerleyen bir iştir.

## 2. Ana kavramlar
- **Görev bağlamı:** Modelin kim olduğunu ve ne yaptığını en başta söylemek.
- **Arka plan bilgisi:** Her seferinde değişmeyen bilgileri (form yapısı gibi) önceden vermek.
- **Örnekler:** İstediğin cevabın bir iki örneğini göstermek.
- **Etiketler:** Bilgiyi <belge> gibi etiketlerle ayırmak; model karıştırmaz.
- **Çıktı biçimi:** Cevabın nasıl görüneceğini açıkça tarif etmek.

## 3. Nasıl uygulanır
1. Sık kullandığın bir prompt'u al ve başına görev bağlamı ekle.
2. Bir örnek cevap ekle ve sonucu karşılaştır.
3. Uzun belgeleri etiketlerle ayır.
4. “Emin değilsen söyle” cümlesini ekle.
5. Her denemeden sonra prompt'u bir adım düzelt.

## Örnekler
- **Kötü prompt:** “Bu yazıyı düzelt” yerine: “Sen bir editörsün. Bu blog yazısını 16 yaşındaki okuyucular için sadeleştir, 300 kelimeyi geçme.”
- **Örnek vermek:** İstediğin tarzda bir paragraf ekleyip “bu tonda yaz” dersin.
- **Etiket kullanmak:** Uzun metni <metin> … </metin> arasına koyup talimatı ayrı yazarsın.
