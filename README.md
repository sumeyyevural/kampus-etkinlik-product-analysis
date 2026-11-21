# Kampüs Etkinlik -- Ürün Keşfi ve Gereksinim Analizi

**Proje türü:** Bireysel portfolyo projesi -- Ürün keşfi ve iş analizi\
**Alan:** Yönetim Bilişim Sistemleri\
**Yıl:** 2026

## Proje özeti

Kampüs Etkinlik, Akdeniz Üniversitesi öğrencilerinin kampüs içerisindeki
sosyal, kültürel, akademik ve sportif etkinlikleri tek bir platform
üzerinden keşfedebilmesini, etkinlik detaylarını inceleyebilmesini ve
çevrim içi kayıt oluşturabilmesini amaçlayan örnek bir dijital ürün
fikridir.

Bu çalışma, ürünün analiz ve tasarım sürecine odaklanan bireysel bir
portfolyo projesidir. Gerçek bir yazılım geliştirme veya canlıya alma
çalışması değildir.

## Problem

Etkinlik duyurularının farklı iletişim kanallarında paylaşılması,
öğrencilerin etkinlikleri tek noktadan takip etmesini zorlaştırabilir.
Etkinlik bilgilerine ve kayıt koşullarına ulaşmak için farklı
kaynakların kontrol edilmesi gerekebilir.

**Önemli not:** Bu problemler ürün keşfi aşamasında oluşturulmuş
başlangıç varsayımlarıdır ve gerçek kullanıcı araştırmasıyla
doğrulanmaları gerekir.

## Ürün hedefi

Öğrencilerin etkinlikleri keşfetme, etkinlik bilgilerine ulaşma ve
etkinliklere kayıt olma süreçlerini merkezi bir dijital platform
üzerinden yönetebilmelerini sağlayacak temel işlevleri tanımlamak.

## Hedef kullanıcılar

-   **Öğrenci:** Etkinlikleri keşfeder, detayları inceler, etkinliklere
    kayıt olur ve kayıtlarını takip eder.
-   **Etkinlik organizatörü:** Etkinlik oluşturur, etkinlik bilgilerini
    günceller ve katılımcıları görüntüler.
-   **Sistem yöneticisi:** Etkinlikleri denetler; onaylar veya reddeder.

Bu profiller temsili kullanıcı profilleridir; gerçek kişilerle yapılmış
görüşmelere dayanmamaktadır.

## Analiz çıktıları

-   Ürün vizyonu ve problem tanımı
-   User Personas
-   Fonksiyonel ve fonksiyonel olmayan gereksinimler
-   11 kullanıcı hikâyesi
-   Kullanıcı hikâyeleri için kabul kriterleri
-   MoSCoW önceliklendirmesi
-   MVP kapsamı
-   Proje kapsamı, varsayımlar ve kısıtlar

## Jira ve çevik çalışma

Projenin iş listesi Jira üzerinde Scrum yaklaşımıyla yapılandırılmıştır.
Çalışma kapsamında:

-   5 Epic oluşturuldu.
-   11 User Story tanımlandı ve ilgili Epic'lerle ilişkilendirildi.
-   Kullanıcı hikâyeleri önceliklendirildi.
-   İşler 3 Sprint altında planlandı ve Sprint süreçleri tamamlandı.

Jira ekran görüntüleri `jira-screenshots/` klasöründe sunulacaktır.

## MVP kapsamı

İlk sürüm için öngörülen temel özellikler:

-   Öğrenci hesabı oluşturma ve giriş
-   Yayınlanmış etkinlikleri görüntüleme
-   Etkinlik detaylarını inceleme
-   Etkinliklere çevrim içi kayıt olma
-   Kendi etkinlik kayıtlarını görüntüleme
-   Organizatörlerin etkinlik oluşturması
-   Kontenjanı dolmuş etkinliklere kayıt yapılmasının engellenmesi
-   Aynı öğrencinin aynı etkinliğe birden fazla kayıt oluşturmasının
    engellenmesi
-   Etkinliklerin yönetici onayından geçmesi

QR kod ile katılım kontrolü, otomatik e-posta bildirimleri ve
gelişmiş/kişiselleştirilmiş öneriler ilk sürüm kapsamı dışında
bırakılmıştır.

## Kullanılan araçlar ve yöntemler

-   **Jira:** Epic, User Story, backlog ve Sprint planlaması
-   **Microsoft Word:** Analiz ve gereksinim dokümantasyonu
-   **Scrum:** İşlerin Sprint'ler halinde planlanması
-   **MoSCoW:** Gereksinim önceliklendirmesi
-   **User Story ve Acceptance Criteria:** Kullanıcı ihtiyaçlarının ve
    beklenen davranışların tanımlanması

## Proje yapısı

``` text
kampus-etkinlik-product-analysis/
├── README.md
├── docs/
│   ├── Project Documentation.docx
│   └── Project-Overview.pdf
└── jira-screenshots/
    ├── Sprint-1.png
    ├── Sprint-2.png
    ├── Sprint-3.png
```

> Klasör ve ekran görüntüsü adlarını GitHub'a yüklediğin gerçek dosya
> adlarıyla eşleştir. Henüz eklemediğin ekran görüntülerini listeden
> çıkarabilir veya daha sonra ekleyebilirsin.

## Kapsam ve sınırlılıklar

-   Proje bireysel portfolyo çalışmasıdır.
-   Gerçek kullanıcı görüşmeleri ve canlı sistem verileri
    kullanılmamıştır.
-   Çalışan bir yazılım ürünü geliştirilmemiştir.
-   Analiz ve ürün yönetimi süreçleri örnek bir senaryo üzerinden
    dokümante edilmiştir.

## Öğrenme ve sergileme amacı

Bu çalışma; ürün keşfi, gereksinim analizi, kullanıcı hikâyesi yazımı,
kabul kriterleri oluşturma, önceliklendirme ve Scrum tabanlı iş takibi
konularındaki uygulamalı çalışmalarımı sergilemek amacıyla
hazırlanmıştır.
