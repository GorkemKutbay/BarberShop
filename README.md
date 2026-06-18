Berberhane — Berber & Kuaför Web Sitesi

Geleneksel berberlik temasıyla tasarlanmış, tek dosyalık (single-file), tamamen statik bir tanıtım sitesi şablonu. Saf HTML/CSS/JS ile yazılmıştır; herhangi bir framework, build aracı veya backend gerektirmez.

Önizleme

berberhane.html dosyasını herhangi bir tarayıcıda açarak siteyi anında görüntüleyebilirsiniz.

Özellikler


Sticky header ve mobil uyumlu hamburger menü
Hero, Hakkımızda, Hizmetler, Ekibimiz, Galeri, Fiyat Listesi, Müşteri Yorumları, Blog ve İletişim bölümleri
Scroll ile ortaya çıkan (reveal) animasyonlar — prefers-reduced-motion desteğiyle
Tamamen responsive tasarım (mobil, tablet, masaüstü)
Elle çizilmiş SVG ikon seti (makas, ustura, tarak vb.) — harici ikon kütüphanesine bağımlılık yok
İletişim formu (randevu/booking sistemi içermez, sadece mesaj formu)
CSS değişkenleri (custom properties) ile kolay tema/renk özelleştirmesi


Kullanılan Teknolojiler


HTML5
CSS3 (Flexbox, Grid, CSS Custom Properties)
Vanilla JavaScript (IntersectionObserver, basit DOM etkileşimleri)
Google Fonts — Anton, Caveat, Work Sans


Klasör Yapısı

berberhane/
└── berberhane.html   # Tüm HTML, CSS ve JS bu dosyada yer alır

Kurulum

Build aracı veya bağımlılık gerekmez.

bashgit clone https://github.com/GorkemKutbay/berberhane.git
cd berberhane

berberhane.html dosyasını tarayıcıda açmanız yeterlidir. İsterseniz Live Server gibi bir araçla da çalıştırabilirsiniz.

Özelleştirme

Ne değiştirilecekNeredeDükkan adı / logo<div class="logo"> (header ve footer)Renk paleti:root içindeki CSS değişkenleri (--gold, --burgundy, --bg vb.)Yazı tipleri<head> içindeki Google Fonts linki ve ilgili CSS kurallarıİletişim bilgileri#iletisim ve footer bölümleriHizmetler / fiyatlar#hizmetler ve #fiyatlar bölümlerindeki kartlarEkip üyeleri#ekibimiz bölümüHarita.map-box içine gerçek Google Haritalar <iframe> embed kodu eklenebilirGaleri görselleri.g-panel öğelerindeki arka plan/ikonlar yerine gerçek fotoğraflar kullanılabilir

Notlar


Bu şablon randevu/rezervasyon (booking) sistemi içermez; iletişim bölümünde yalnızca genel bir mesaj formu bulunur.
Galeri ve ekip görselleri için yer tutucu (placeholder) SVG/CSS illüstrasyonlar kullanılmıştır; gerçek fotoğraflarla değiştirilmesi önerilir.


Lisans

Bu proje kişisel/portföy kullanımı için ad belirtmek üzere serbestçe değiştirilebilir ve kullanılabilir.

Yazar

Görkem Kutbay
GitHub: @GorkemKutbay
