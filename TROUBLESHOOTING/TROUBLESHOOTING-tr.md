## UCP3 Arayüzü başlamıyor (1 saniye sonra kapanıyor)
[webview2 runtime](https://developer.microsoft.com/en-us/microsoft-edge/webview2/) paketinin kurulu olduğundan emin olun.
Eğer bu sorunu çözmezse, [yüklü uygulamalar](https://support.microsoft.com/en-us/windows/repair-apps-and-programs-in-windows-e90eefe4-d0a2-7c1b-dd59-949a9030f317) listenizden webview2 runtime'ı onarmayı deneyin.
Bu da işe yaramazsa, [şunu](https://superuser.com/a/1751710) deneyebilirsiniz.

## Modlama altyapısını kullanırken oyun hiç başlamıyor (pencere gelmiyor)

1. Microsoft'un [Visual C++ for x86'in bu sürümünü](https://aka.ms/vs/17/release/vc_redist.x86.exe) yüklediğinizden emin olun.

2. Hâlâ sorun mu yaşıyorsunuz? Oyunu komut satırından çalıştırmayı deneyin. Şu komutu kullanın:
    +++cmd
    "Stronghold Crusader.exe" --ucp-console --ucp-verbosity 10 --ucp-console-verbosity 10
    +++

3. Eğer bu komut herhangi bir uyarı veya hata göstermezse, lütfen GitHub üzerinden bizimle iletişime geçin veya [Discord sunucumuza](https://discord.gg/P9dkF38Q2t) katılın!

---

## Oyun başlarken hatalar gösteriyor

Eğer hatalarda **"AOB"** ifadesi geçiyorsa, muhtemelen desteklenmeyen bir oyun sürümü kullanıyorsunuz.

- Yama resmi olarak **sürüm 1.41** ve **1.41.1** (Latin dilleri) ile çalışmaktadır.
- Farklı bir sürümünüz varsa, Firefly'ın [Crusader HD Yaması](http://www.strongholdcrusaderhd.com/patch.html) ile ücretsiz olarak 1.41 sürümüne yükseltebilir veya oyunu Steam'den satın alabilirsiniz.

### Steam'de oyun dili nasıl değiştirilir?
[Bu Steam sayfasının](https://help.steampowered.com/en/faqs/view/4984-C127-121D-B3F2) altındaki talimatları izleyin.

---

## En sevdiğim eklenti neden çalışmıyor?

Favori eklentinizin, aktif eklentiler listesinin **en üstünde** olduğundan emin olun.

- **Neden?** Eklentiler listede aşağıdan yukarıya doğru uygulanır.
- Listede daha yukarıda olan eklentiler, daha aşağıda olanların **üzerine yazar**.

---

## "AI" ve "AI applied" (Uygulanmış AI) arasındaki fark nedir?

- **AI eklentileri** ("Applied" olmadan) yeni AI dosyaları (içerik) ekler.
- **"AI Applied" eklentileri** ise yeni AI yapılandırmasını mevcut AI yuvalarına uygular.
   Örnek: Eski Sıçan (Rat) yapay zekasının yerine yeni bir Sıçan yapay zekasının gelmesi.

### AI dosyalarını kendiniz mi özelleştirmek istiyorsunuz?
Eğer sadece yeni AI içeriğine ihtiyacınız varsa, **AI eklentilerini** ("Applied" olmadan) etkinleştirin.
Örneğin, iki Sıçan'ın kapışması için Yılan'ın (Snake) AI yuvasına yeni bir Sıçan AI'ı yerleştirebilirsiniz.

---

## Savaş Sandığı Patikası oyunu çökertiyor
[Şu sayfaya](https://steamcommunity.com/app/40970/discussions/0/1777135944135270096/) göz atın.

## Diğer sorunlar

Başka sorunlar yaşarsanız, lütfen GitHub üzerinden bize ulaşın veya [Discord sunucumuza](https://discord.gg/P9dkF38Q2t) katılın!