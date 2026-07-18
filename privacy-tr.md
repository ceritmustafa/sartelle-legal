---
title: Gizlilik Politikası
permalink: /privacy-tr/
---

# Sartelle Gizlilik Politikası

**Yürürlük tarihi: 18 Temmuz 2026**

Sartelle ("Uygulama", "biz"), Mustafa Cerit ("İşletmeci") tarafından
işletilen bir yapay zekâ destekli kişisel stil ve dijital gardırop
uygulamasıdır. Bu politika; hangi kişisel verileri, neden, nerede
işlediğimizi ve haklarınızı açıklar. 6698 sayılı Kişisel Verilerin
Korunması Kanunu (KVKK) kapsamındaki aydınlatma yükümlülüğü bu metinle
yerine getirilir. AEA/Birleşik Krallık kullanıcıları için GDPR/UK GDPR
uygulanır.

## 1. Veri sorumlusu

Veri sorumlusu İşletmeci'dir: **mustafa@mustafacerit.com**

## 2. İşlenen veriler

### 2.1 Hesap verileri
- **Giriş kimliği.** Yalnızca Apple ile Giriş ve Google ile Giriş
  desteklenir. Benzersiz bir tanımlayıcı ile, girişte izin vermenize bağlı
  olarak ad ve e-posta adresinizi alırız (Apple'ın e-posta gizleme özelliği
  tam olarak desteklenir). Apple veya Google şifrenizi asla görmeyiz.
- **Dil ve tercihler** (onboarding yanıtları, stil tercihleri vb.).

### 2.2 Gardırop içeriği
- **Yüklediğiniz kıyafet fotoğrafları** ve bunlardan ürettiğimiz türev
  görseller (arka planı ayrılmış kesitler, önizlemeler, kombin görselleri).
- **AI analizinin ürettiği kıyafet metadatası** (kategori, renk, öznitelik)
  ve yaptığınız düzenlemeler.

Fotoğraflarınız size aittir. Yalnızca Uygulama'nın özelliklerini size
sunmak için işlenir; AI modellerini eğitmek için **kullanılmaz**, satılmaz
ve başka kullanıcılara gösterilmez.

### 2.3 Kullanım ve faturalandırma verileri
- **AI kullanım kayıtları** (iş türü, zaman damgası, token/maliyet
  muhasebesi) — kota, kötüye kullanım önleme ve fatura bütünlüğü için.
- **Abonelik durumu** Apple Uygulama İçi Satın Alma üzerinden, RevenueCat
  aracılığıyla işlenir. Kart bilgilerinizi hiçbir zaman görmeyiz.

### 2.4 Teknik veriler
- **Loglar:** istek kimliği, zaman damgası, genel cihaz/uygulama sürümü ve
  hata ayrıntıları. Log politikamız fotoğraf, token ve mesaj içeriklerinin
  loglanmasını yasaklar.
- Reklam tanımlayıcısı toplamayız; üçüncü taraf reklam/izleme SDK'sı
  kullanmayız.

## 3. İşleme amaçları ve hukuki sebepler

| Amaç | Veri | Hukuki sebep (KVKK m.5) |
| --- | --- | --- |
| Giriş ve hesabın sağlanması | Hesap verileri | Sözleşmenin ifası |
| Dijital gardırop, AI analizi, kombin üretimi | Gardırop içeriği | Sözleşmenin ifası |
| Kota, dolandırıcılık ve kötüye kullanım önleme | Kullanım kayıtları, loglar | Meşru menfaat |
| Abonelik ve yetkilendirmeler | Faturalandırma verileri | Sözleşmenin ifası; hukuki yükümlülük |
| Güvenlik izleme ve denetim | Loglar, denetim kayıtları | Meşru menfaat; hukuki yükümlülük |

Hukuki veya benzeri önemli sonuç doğuran otomatik karar verme yapılmaz; AI
yalnızca stil önerileri üretir.

## 4. Yapay zekâ işleme

Kıyafet analizi ve görsel üretimi **Microsoft Azure OpenAI Service**
üzerinde, **AB (İsveç) bölgesinde** çalışır. Microsoft'un koşulları
uyarınca Azure OpenAI'a gönderilen veriler temel modellerin eğitiminde
**kullanılmaz** ve OpenAI şirketiyle paylaşılmaz. Servislerimiz Azure'a
yönetilen kimlikle bağlanır; Uygulama'da veya cihazlarda uzun ömürlü AI
anahtarı bulunmaz.

## 5. Verilerin bulunduğu yer

- **Backend ve görseller:** Microsoft Azure, İsveç (AB).
- **Kimlik doğrulama:** Supabase.
- **Abonelik durumu:** RevenueCat.
- **Apple:** satın alma ve App Store/TestFlight dağıtımı.

Yurt dışına aktarım gereken hallerde ilgili sağlayıcının standart
sözleşme hükümleri veya eşdeğer güvenceleri esas alınır.

## 6. Saklama süreleri

- Gardırop içeriği ve hesap verileri: hesabınız aktif olduğu sürece.
- Silinen kıyafetler ve türevleri: zamanlanmış temizlik işiyle depodan
  kaldırılır.
- Hesap silme: hesap verilerinizi, gardırop içeriğinizi ve türev
  görselleri kaldırır; muhasebe ve kötüye kullanım önleme için gereken
  anonimleştirilmiş toplamlar saklanabilir.
- Loglar: sınırlı bir operasyonel süre sonunda silinir.

## 7. Haklarınız (KVKK m.11)

Uygulama içinden dilediğiniz an:

- **Verilerinizi dışa aktarabilirsiniz** — Ayarlar → Gizlilik → Dışa aktar.
- **Hesabınızı ve verilerinizi silebilirsiniz** — Ayarlar → Gizlilik →
  Hesabı sil.

Ayrıca verilerinize erişme, düzeltme, işlemeyi kısıtlama, itiraz etme ve
Kişisel Verileri Koruma Kurumu'na şikâyette bulunma hakkına sahipsiniz.
Talepleriniz için **mustafa@mustafacerit.com** — en geç 30 gün içinde
yanıtlanır.

## 8. Güvenlik

- Her yerde aktarım şifrelemesi (TLS); depoda şifreleme.
- Veritabanında satır düzeyi güvenlik: her hesap yalnızca kendi
  satırlarına erişebilir.
- Sıfır güven servis kimlikleri: paylaşılan anahtarlar yerine yönetilen
  kimlikler; mobil uygulamaya hiçbir AI veya depolama kimlik bilgisi
  gömülmez.
- Yönetimsel erişim isimli ve tek tek kimliği doğrulanmış operatörlerle
  sınırlıdır; her yönetimsel işlem denetim loguna yazılır.

## 9. Çocuklar

Sartelle 13 yaş altına (veya bulunduğunuz ülkedeki daha yüksek asgari
yaşa) yönelik değildir. Bir çocuğun hesap açtığını düşünüyorsanız bize
yazın; hesabı sileriz.

## 10. Değişiklikler

Değişiklikler bu depoda yayımlanır ve yürürlük tarihi güncellenir. Önemli
değişiklikler yürürlüğe girmeden önce Uygulama içinde duyurulur.

## 11. İletişim

**mustafa@mustafacerit.com**
