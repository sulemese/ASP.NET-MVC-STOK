# ASP.NET MVC Stok Takip Uygulaması

Bu proje, **ASP.NET MVC 5** kullanılarak geliştirilmiş bir stok takip sistemidir. Veritabanı işlemleri **Entity Framework Database-First** yaklaşımıyla gerçekleştirilmiştir. Uygulamada temel olarak kategori, ürün, müşteri ve personel yönetimi yapılabilmektedir.

## 🚀 Özellikler

- Bootstrap 3 ile şık ve responsive tasarım
- Data Annotation + `@Html.ValidationMessageFor` ile form doğrulama (validasyon)
- Entity Framework 6 ile SQL Server veritabanı bağlantısı
- Html Helpers (`@Html.TextBoxFor`, `@Html.DropDownListFor` vb.) ile dinamik ve okunabilir Razor View sayfaları
- PagedList.Mvc NuGet paketi ile liste sayfalarında sayfalama (pagination) özelliği
- Katmanlı mimari prensipleriyle temiz ve düzenli kod yapısı

## 🛠️ Kullanılan Teknolojiler

- ASP.NET MVC 5
- Entity Framework 6 (Database-First)
- SQL Server
- Bootstrap 3
- LINQ
- Razor View Engine
- PagedList.Mvc (NuGet Paketi)

## 🗃️ Veritabanı Tasarımı

Aşağıdaki tablolar kullanılmıştır:

- **Kategoriler:** KategoriId, KategoriAdi, Aciklama
- **Ürünler:** UrunId, UrunAdi, KategoriId, StokAdet, BirimFiyat, Barkod, EklenmeTarihi
- **Müşteriler:** MusteriId, Ad, Soyad, Email, Telefon, Adres
- **Personeller:** PersonelId, Ad, Soyad, Email, Telefon, Pozisyon, AktifMi
- **StokHareketleri:** HareketId, UrunId, Miktar, Tarih, PersonelId, Aciklama, HareketTipi

## 📄 Yeni Eklenen Özellikler

- ✅ `@Html.ValidationMessageFor` ile kullanıcı dostu validasyon mesajları eklendi
- ✅ Formlarda Html Helpers aktif şekilde kullanılarak kod okunabilirliği ve bakım kolaylığı artırıldı
- ✅ Uzun veri listelerinde sayfalama (pagination) desteği sağlandı (`PagedList.Mvc` kullanılarak)

## ⚙️ Kurulum Adımları

1. Bu projeyi indir veya klonla:

   ```bash
   git clone https://github.com/sulemese/ASP.NET-MVC-STOK.git

## NOTLAR
Proje tamamen örnek ve eğitim amaçlı geliştirilmiştir.
