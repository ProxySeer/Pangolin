# Pangolin Security

**Pangolin**, dosyalarınızı güvenli şekilde şifrelemek, çözmek ve şifreli dosyaları diske açmadan önizlemek için geliştirilmiş bir güvenlik uygulamasıdır.

Bu proje, yaklaşık 6 yıl önce geliştirilen **VTCrypt** fikrinin daha sade, daha modern ve eklenti destekli yeni versiyonudur.

## Nedir?

Pangolin ile tüm dosyalarınızı şifreleyebilir, `.encx` formatında saklayabilir ve desteklenen dosyaları **Ghost View** özelliği ile HDD üzerine decrypt etmeden önizleyebilirsiniz.

Ghost View sayesinde dosya geçici olarak dışarı çıkarılmaz; mümkün olan senaryolarda içerik doğrudan güvenli görüntüleme katmanında açılır.

## Özellikler

- Dosya ve klasör şifreleme
- Şifreli dosya çözme
- `.encx` dosya formatı
- Drag & Drop ile hızlı kullanım
- Session Master Password desteği
- Quick Encrypt / Quick Decrypt desteği
- Ghost View ile şifreli dosya önizleme
- Plugin tabanlı mimari
- Windows context menu entegrasyonu
- Tek EXE içine güvenli paketleme
- Paket içeriğini dışarı çıkarmadan önizleme

## Mevcut Pluginler

### Pangolin Media Player Plugin

Şifrelenmiş medya dosyalarını decrypt etmeden Ghost View ile doğrudan oynatmanızı sağlar.

Desteklenen içerikler:

- Video dosyaları
- Ses dosyaları
- Yaygın medya formatları

### Pangolin Shell Plugin

Windows sağ tık menüsü entegrasyonu sağlar.

Bu plugin ile dosyalar üzerinde doğrudan:

- Encrypt
- Decrypt
- Ghost View

işlemleri yapılabilir.

> Not: Bu plugin Windows shell entegrasyonu yaptığı için admin yetkisi gerektirir.

### Pangolin Packer Plugin

Dosyalarınızı bir vault mantığıyla tek bir EXE içine güvenli şekilde paketler.

Paketlenen dosyalar:

- Şifreli olarak saklanır
- Dışarı açılmadan önizlenebilir
- Parola olmadan çalıştırılamaz
- Hedef bilgisayarda ilgili uygulama kurulu olmasa bile görüntülenebilir

Örneğin Word, Excel veya PDF dosyalarını paketlediğinizde Pangolin size tek bir EXE oluşturur. Bu EXE parola ile açılır ve desteklenen dosyalar Ghost View ile görüntülenebilir.

## Kullanım Senaryoları

- Kişisel dosyaları güvenli saklama
- USB disklerde şifreli arşiv taşıma
- Medya dosyalarını güvenli izleme
- Belgeleri dışarı açmadan önizleme
- Tek EXE halinde güvenli dosya paylaşımı
- Office veya PDF okuyucu olmayan bilgisayarlarda güvenli görüntüleme

## Güvenlik Yaklaşımı

Pangolin’in temel amacı, dosyaların mümkün olduğunca diske açık halde yazılmadan işlenmesidir.

Özellikle Ghost View ve Packer özellikleri, hassas dosyaların geçici klasörlere açık şekilde çıkarılmasını azaltmak için tasarlanmıştır.

## Proje Durumu

Bu proje aktif geliştirme aşamasındadır.

Mevcut ana bileşenler:

- Pangolin Security ana uygulaması
- Media Player Plugin
- Shell Plugin
- Packer Plugin
- Ghost View altyapısı
- Plugin yönetim sistemi

## Planlanan Özellikler

- Daha fazla dosya tipi için Ghost View desteği
- Gelişmiş paketleme seçenekleri
- Daha güçlü plugin API
- Daha iyi işlem kuyruğu ve progress ekranı
- Otomatik plugin güncelleme sistemi
- Daha gelişmiş güvenlik logları

## Lisans

Lisans bilgisi daha sonra eklenecektir.

## Uyarı

Pangolin güvenlik odaklı bir uygulamadır. Parolanızı unutmanız durumunda şifrelenmiş dosyalarınızı geri getirmeniz mümkün olmayabilir.
