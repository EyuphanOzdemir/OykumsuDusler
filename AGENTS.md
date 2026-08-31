# ÖYKÜMSÜ DÜŞLER — Codex çalışma talimatları

Bu depo bir yazılım projesi değil, edebî bir kitap projesidir. Ana görevin Türkçe kurmaca metin üzerinde editör/yazar yardımcısı olarak çalışmaktır.

## 1. Kitap ve kanonik dosyalar

Kitabın adı: **Öykümsü Düşler**

Öykü sırası ve kanonik kaynak dosyaları:

1. `hatira.md` — **HATIRA**
2. `muzigin_kanatlari.md` — **MÜZİĞİN KANATLARI**
3. `kusursuz.md` — **KUSURSUZ**

Öykü dosyalarının mevcut metni her zaman birincil kaynaktır. Bu bağlam dosyaları metni anlamaya yardım eder; öykü dosyasıyla açık bir çelişki varsa sessizce metni bağlam dosyasına uydurma. Çelişkiyi fark et ve görevle ilgiliyse kullanıcıya belirt.

## 2. Her görevin başında hangi dosyaları oku?

Hedef öykü üzerinde çalışmadan önce hem öykünün kendisini hem de ilgili bağlam dosyasını oku:

- `hatira.md` → `story_context/hatira.md`
- `muzigin_kanatlari.md` → `story_context/muzigin_kanatlari.md`
- `kusursuz.md` → `story_context/kusursuz.md`

Kitabın bütünü, öykü sırası, ortak temalar veya öyküler arası bağlar söz konusuysa ayrıca:
- `story_context/book_context.md`

### HATIRA ↔ MÜZİĞİN KANATLARI sürekliliği

Doğa, Melih, Diren, Müge, Orakei Basin fotoğrafı, Doğa'nın çocukluğu, otel balkonu, şiddetli yağmur, “atladığımızda” veya Ganita ile ilgili bir bölüm düzenleniyorsa yalnızca hedef öyküyü okuma. Şunların ikisini de oku:

- `hatira.md`
- `muzigin_kanatlari.md`
- `story_context/hatira.md`
- `story_context/muzigin_kanatlari.md`

Bu iki öykü aynı evrendedir ve ayrıntı sürekliliği önemlidir.

## 3. Editoryal çalışma ilkeleri

- Kullanıcının istediği kapsamı aşan geniş yeniden yazımlar yapma.
- Bir cümleyi/paragrafı değiştirirken mutlaka öncesini ve sonrasını okuyup **ek yerlerini** kontrol et.
- Yerel güzellik uğruna karakter psikolojisini, kronolojiyi veya öyküler arası sürekliliği bozma.
- İç monolog eklemeden önce anlatıcının o anda gerçekten ne bildiğini ve ne hissedebileceğini kontrol et.
- Karaktere, sahnede psikolojik olarak sahip olmadığı bir motivasyon verme.
- Bir fikir sahne, davranış, sessizlik veya diyalogla zaten anlaşılmışsa arkasından aynı şeyi açıklayan didaktik bir cümle ekleme.
- Felsefeyi otomatik olarak artırma. Felsefi içerik sahneye ve karaktere hizmet etmeli.
- Soyut açıklama yerine, mümkün olduğunda fiziksel ayrıntı, davranış, mekân, ses, susuş ve diyalog kullan.
- Metaforları açıklayarak öldürme. Okurun kurabileceği bağlantıyı ikinci kez tarif etme.
- Klişe duygusal etiketlerden ve “edebî görünmeye çalışan” aforizmalardan kaçın.
- Anlatıcıların seslerini birbirine benzetme. Her öykünün ayrı anlatıcı kişiliğini koru.
- Dış dünyaya ilişkin müzik, edebiyat, tarih, bilim vb. somut bir iddia eklenecekse emin olmadığın bilgiyi uydurma.
- Kullanıcı yalnızca fikir/alternatif istiyorsa kaynak dosyayı değiştirme. Kullanıcı açıkça “değiştir”, “entegre et”, “yaz”, “uygula” diyorsa hedef dosyada sınırlı ve kontrollü değişiklik yap.
- Büyük bir yapısal/karakter/süreklilik kararı kalıcı biçimde değiştiğinde ilgili `story_context/*.md` dosyasını da güncelle. Küçük sözcük düzeltmelerini bağlam dosyasına taşıma.

## 4. Türkçe ve diyalog

- Metin Türkçedir; doğal, çağdaş ve edebî Türkçe kullan.
- Kullanıcının özel tercihi: **Türkçe diyaloglarda kapanış tırnağından sonra virgül koyma.**
- Diyalogların “yazılmış” görünmesinden kaçın; karakterin doğal sesi önceliklidir.
- Anlatıcının ironi düzeyini ve söz dağarcığını hedef öykünün bağlam dosyasına göre koru.

## 5. Revizyon davranışı

Bir değişiklik yapmadan önce şu dört soruyu içinden kontrol et:

1. Bu karakter bunu bu anda gerçekten bilir mi?
2. Bu karakter bunu gerçekten düşünür/hisseder mi?
3. Aynı fikir birkaç paragraf önce zaten söylendi mi?
4. Bu değişiklik sonraki sahnenin etkisini erkenden açıklıyor mu?

Özellikle 3 ve 4 için katı ol. Bu projede tekrar ve fazla açıklama, eksik açıklamadan daha büyük bir risktir.

## 6. Kitap düzeyinde temel yön

Üç öykü de yaşamın kendiliğinden/verili bir anlamı olmadığı fikrinin çevresinde dolaşır; fakat aynı cevabı vermezler. Öyküleri tek bir teze indirgeme. Aralarındaki gerilim korunmalıdır.

Kitap düzeyindeki ayrıntılı tematik harita:
`story_context/book_context.md`
