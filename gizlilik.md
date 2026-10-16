---
title: Gizlilik Politikası
lang: tr
---

# Halfie Gizlilik Politikası ve KVKK Aydınlatma Metni

[English](privacy) · [Destek](./)

**Son güncelleme:** 17 Ekim 2026

## 1. Veri sorumlusu

Hakan Kaya (bireysel geliştirici) · e-posta: [official.mediatv.tr@gmail.com](mailto:official.mediatv.tr@gmail.com)

## 2. Kısaca

Halfie, eşleşmiş iki kişinin ortak listeleri, notları, etkinlikleri ve sohbeti için bir uygulamadır.
**Listeleriniz, notlarınız, etkinlikleriniz, mesajlarınız ve acil durumda paylaştığınız konum uçtan uca şifrelidir:**
yalnızca sizin ve eşinizin telefonunda okunabilir. Biz (Halfie) bu içerikleri göremeyiz.

Reklam, analiz/izleme aracı ve üçüncü taraf takip **kullanılmaz**. Verileriniz satılmaz.

## 3. İşlenen kişisel veriler

| Veri | Neden | Nerede | Ne kadar süre |
|---|---|---|---|
| E-posta adresi | Hesap oluşturma ve giriş | Sunucu (Supabase, Frankfurt/AB) | Hesap silinene kadar |
| Görünen ad | Eşinize kim olduğunuzu göstermek | Sunucu | Hesap silinene kadar |
| Kullanıcı kimliği, eşleşme bilgisi | Sizi eşinizle eşleştirmek | Sunucu | Hesap silinene / eşleşme bitene kadar |
| Şifreleme açık anahtarı | Eşinizin size şifreli veri gönderebilmesi | Sunucu | Hesap silinene kadar |
| Şifreli paketler (içeriği okunamaz) | Değişikliklerin eşinize iletilmesi | Sunucu | Eşiniz teslim alınca silinir; en geç 30 gün |
| Paket üstverisi (kimden, kime, ne zaman, boyut) | İletim | Sunucu | Paketle birlikte silinir |
| Bildirim adresi (Apple'ın verdiği cihaz adresi), uygulama dili, seçtiğiniz bildirim sesleri | Eşiniz bir şey gönderdiğinde size bildirim göstermek | Sunucu | Çıkış yapınca, hesap silinince ya da Apple adresi geçersiz sayınca silinir |
| Bildirim türü ve zamanı (mesaj / kalp / hediye / acil) | Bildirimin gönderilmesi | Sunucudan ve Apple'dan geçer, saklanmaz | — |
| Listeler, notlar, etkinlikler, mesajlar | Uygulamanın kendisi | **Yalnızca telefonlarınızda** | Siz silene / eşleşme bitene kadar |
| Konum (yalnızca acil uyarı gönderdiğinizde) | Eşinizin size ulaşabilmesi | Şifreli olarak eşinizin telefonuna | Sohbetteki mesajla birlikte |
| Eşinizin telefon numarası (girerseniz) | Sohbetten arama | **Yalnızca kendi telefonunuzda** | Eşleşme bitene kadar |

Bildirimde mesajın içeriği **gönderilmez**; yalnızca gönderenin adı ve "Yeni mesaj" gibi bir tür yazısı görünür.

## 4. İsteğe bağlı özellikler

- **iCloud yedeği (varsayılan kapalı):** Açarsanız verilerinizin bir kopyası, telefonda şifrelenip **kendi iCloud
  Drive'ınızda** saklanır. Şifre anahtarı iCloud Anahtar Zinciri'nde durur. Halfie bu dosyaya erişemez. Yedeği
  Ayarlar → iCloud yedeği bölümünden kapatabilir, iPhone Ayarları → iCloud bölümünden silebilirsiniz.
- **Yeni telefona geri yükleme:** Telefon değiştirdiğinizde ortak verileriniz, eşinizin onayıyla onun telefonundan
  uçtan uca şifreli olarak size gönderilir.
- **Satın almalar (Halfie+, hediyeler):** Ödeme Apple tarafından alınır; kart bilgilerinizi görmeyiz. Aboneliğinizin
  eşinizle paylaşılması uçtan uca şifreli bir paketle yapılır.

## 5. Hukuki sebep (KVKK m.5)

- Sözleşmenin kurulması ve ifası (hesabınızın, eşleşmenizin ve bildirimlerin çalışması),
- Acil konum paylaşımı ve iCloud yedeği için: sizin açık eyleminiz ve iOS izinleriniz.

## 6. Aktarım

Sunucu hizmeti Supabase Inc. tarafından Avrupa Birliği'nde (Frankfurt) barındırılır. Bildirimler Apple Push
Notification Service, ödemeler App Store, isteğe bağlı yedek iCloud üzerinden Apple Inc. tarafından işlenir. Bu,
kişisel verilerin **yurt dışına aktarımı** anlamına gelir (KVKK m.9). Uçtan uca şifreli içerikler bu sağlayıcılar
tarafından okunamaz.

## 7. Haklarınız (KVKK m.11)

Verilerinizin işlenip işlenmediğini öğrenme, bilgi talep etme, düzeltme, silme, itiraz ve diğer haklarınız için
[official.mediatv.tr@gmail.com](mailto:official.mediatv.tr@gmail.com) adresine yazabilirsiniz.

**Hesabınızı uygulama içinden silebilirsiniz:** Ayarlar → Hesabı sil. Bu işlem sunucudaki hesap, eşleşme,
anahtar, bildirim adresi ve bekleyen paketleri kalıcı olarak siler; telefonunuzdaki veriler de silinir.
Eşinizin telefonundaki kopyaları ve kendi iCloud'unuzdaki yedeği biz silemeyiz.

## 8. Güvenlik

İletim TLS ile, içerik ayrıca uçtan uca (X25519 + ChaCha20-Poly1305) şifrelenir. Telefondaki veriler iOS Veri
Koruması ile korunur. Eşinizle aynı şifreleme anahtarını kullandığınızı Ayarlar → Uçtan uca şifreleme bölümündeki
güvenlik koduyla karşılaştırarak doğrulayabilirsiniz.

## 9. Yaş sınırı

Halfie 18 yaş ve üzeri kullanıcılar içindir.

## 10. Değişiklikler

Bu politika değişirse uygulama içinde ve bu sayfada duyurulur.
