<h1 align="center">DevTrack</h1>

<p align="center">
  Projelerini alt görevlere bölüp ilerlemeni yüzde olarak takip ettiğin planlama uygulaması.<br>
  Geliştiriciler düşünülerek tasarlandı, herkes kullanabilir.
</p>

---

## Proje hakkında

DevTrack, üzerinde çalıştığın projeleri düzenli ve sistematik biçimde takip
etmeni, ilerlemeni kayıt altına almanı sağlayan bir Android uygulamasıdır.
Geliştirici odaklıdır, ancak planlı çalışmak isteyen herkes için uygundur.

## Neden yaptım?

Amacım sistematik bir çalışma planı oluşturmayı kolaylaştıran bir araç ortaya
koymaktı. Bu projeyle birlikte Jetpack Compose bilgimi pekiştirdim ve temel
animasyon kütüphaneleri üzerinde pratik yaptım.

## Özellikler

| | |
|---|---|
| **Proje listesi** | Projelerini tek ekranda listeleme |
| **Alt görevler** | Her projeye alt görev ekleme ve tamamlandı olarak işaretleme |
| **İlerleme yüzdesi** | Tamamlanan alt görevlerin toplam alt görevlere oranı hesaplanır ve ekranda gösterilir |
| **Hesap** | Firebase Authentication ile kullanıcı hesabı |
| **Yedekleme** | Projeler cihazda saklanır ve Firestore'a yedeklenir |

## Nasıl çalışıyor?

```
Arayüz (Jetpack Compose + Navigation)
        │
        ├── Room ........ projeler ve alt görevler cihazda tutulur
        │
        └── Firebase .... Authentication (hesap) + Firestore (bulut kopyası / yedek)
```

Uygulama yerel veritabanı ile Firestore'u birlikte kullanır: veriler cihazda
Room'da tutulur, Firestore aynı verinin buluttaki kopyasını saklayarak yedek
görevi de görür.

## Kullanılan teknolojiler

| Katman | Teknoloji |
|---|---|
| Dil | Kotlin |
| Arayüz | Jetpack Compose, Compose animasyonları |
| Gezinme | Navigation |
| Yerel veri | Room |
| Bulut | Firebase Authentication, Cloud Firestore |

### Yapay zekâ kullanımı

Kodlama sürecinde yapay zekâ destekli araçlardan yararlandım; uygulamadaki
görseller yapay zekâ ile üretildi.

## Durum

Proje tamamlandı. Arayüz dili Türkçedir.

## Kaynak kod

Kaynak kod özel bir depoda tutuluyor; inceleme için talep üzerine paylaşılabilir.

## İletişim

**osmnnuri** · [GitHub](https://github.com/osmnnuri) · osmannuriyasar57@gmail.com
