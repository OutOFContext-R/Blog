---
baslik: "LLM'lerin içi: derin dalış"
bolum: ai
kaynak: "ANDREJ KARPATHY"
sure: "3 SA 31 DK"
video: "https://www.youtube.com/watch?v=7xTGNNLPyMI"
video_dogrulandi: true
kaynak_reel: "AI bölümü, LLM mekanikleri"
dogrulama: "Transkriptten doğrulanmadı."
---

# LLM'lerin içi: derin dalış

## 1. Kısa özet
Karpathy, ChatGPT gibi bir modelin sıfırdan nasıl yapıldığını kodsuz anlatıyor. Önce internetten toplanan devasa metinle bir “temel model” eğitilir; bu model sadece bir sonraki token'ı tahmin eder. Sonra örnek sohbetlerle asistan gibi davranması öğretilir. En sonda pekiştirmeli öğrenme ile düşünmeyi öğrenir. Bu adımları bilmek, modelin neden hata yaptığını ve nasıl daha iyi kullanılacağını anlamanı sağlar.

## 2. Ana kavramlar
- **Ön eğitim:** İnternet metinleriyle bir sonraki token'ı tahmin etmeyi öğrenmek.
- **Temel model:** Henüz asistan olmayan, internet belgesi taklit eden model.
- **Son eğitim (SFT):** Örnek sohbetlerle modele asistan gibi konuşmayı öğretmek.
- **Halüsinasyon:** Bilmediği yerde emin görünen ama uydurma cevap vermesi.
- **Düşünmek için token:** Model hesabı token token yapar; zor işi adımlara bölmek ona yardım eder.
- **Pekiştirmeli öğrenme:** Modelin deneme yanılmayla kendi çözüm yolunu bulması.

## 3. Nasıl uygulanır
1. Zor bir soruda “adım adım düşün” de ve farkı gör.
2. Modelin emin olduğu bir bilgiyi kaynağıyla doğrulat.
3. Saymak, harf işlemek gibi işleri koda yaptır.
4. Bir cevabı beğenmezsen aynı soruyu yeni sohbette tekrar sor.
