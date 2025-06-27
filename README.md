# ASP.NET MVC Stok Takip Uygulaması

Bu proje, **ASP.NET MVC 5** kullanılarak geliştirilmiş  bir **stok takip sistemidir**. Veritabanı işlemleri **Entity Framework Database-First** yaklaşımıyla gerçekleştirilmiştir. Uygulamada temel olarak **kategori, ürün, müşteri ve personel** yönetimi yapılabilmektedir.

## 🚀 Özellikler

- Bootstrap 3 ile şık ve responsive tasarım
- Data Annotation ile form doğrulama (validasyon)
- Entity Framework ile SQL Server veritabanı bağlantısı
- Katmanlı yapı prensipleriyle kod düzeni

## 🛠️ Kullanılan Teknolojiler

- ASP.NET MVC 5
- Entity Framework 6 (Database-First)
- SQL Server
- Bootstrap 3
- LINQ
- Razor View Engine

## 🗃️ Veritabanı Tasarımı

Aşağıdaki tablolar kullanılmıştır:

- **Kategoriler**: KategoriId, KategoriAdi, Aciklama
- **Ürünler**: UrunId, UrunAdi, KategoriId, StokAdet, BirimFiyat, Barkod, EklenmeTarihi
- **Müşteriler**: MusteriId, Ad, Soyad, Email, Telefon, Adres
- **Personeller**: PersonelId, Ad, Soyad, Email, Telefon, Pozisyon, AktifMi
- **StokHareketleri**: HareketId, UrunId, Miktar, Tarih, PersonelId, Aciklama, HareketTipi

## ⚙️ Kurulum Adımları

1. Bu projeyi indir veya klonla:

   ```bash
   git clone https://github.com/sulemese/ASP.NET-MVC-STOK.git
