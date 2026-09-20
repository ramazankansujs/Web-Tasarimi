
# HTML Temelleri Rehberi 

Hoş geldin! Bu rehber, web geliştirme dünyasının ilk ve en önemli adımı olan **HTML (HyperText Markup Language)** dilini en temel, anlaşılır ve akılda kalıcı şekilde öğrenmen için hazırdır. 

---

## 1. HTML Nedir? (HyperText Markup Language)

* **Tanım:** HTML, bir web sayfasının **iskeletini** ve **içeriğini** oluşturan işaretleme dilidir (Programlama dili değildir).
* **Görevi:** Tarayıcılara (Chrome, Safari, Firefox vb.) sayfada neyin bulunduğunu söyler. Metinler, paragraflar, görseller, videolar ve bağlantılar HTML etiketleri yardımıyla sayfaya eklenir.
* **Çalışma Mantığı:** Etiketler (Tags) mantığıyla çalışır. Çoğu etiket bir açılış (`<etiket>`) ve bir kapanış (`</etiket>`) etiketine sahiptir.

---

## 2. Temel HTML Sayfa İskeleti

Her web sitesinin arkasında standart bir iskelet bulunur. Aşağıdaki şablon, sıfırdan bir HTML dosyası oluşturmak için bilmen gereken en temel yapıdır:

```html
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <title>İlk Web Sayfam</title>
</head>
<body>
    <h1>Merhaba Dünya!</h1>
    <p>Bu benim ilk paragrafım.</p>
</body>
</html>
```

### Kodun Parçaları Ne Anlama Geliyor?
* `<!DOCTYPE html>`: Tarayıcıya bu belgenin güncel HTML5 standartlarında yazıldığını söyler.
* `<html>`: Tüm HTML kodlarının içine yazıldığı kök (ana) etikettir. `lang="tr"` ise sayfanın Türkçe olduğunu belirtir.
* `<head>`: Ziyaretçinin ekranda doğrudan görmediği; ancak tarayıcı ve arama motorları için hayati önem taşıyan arka plan bilgilerinin (sayfa başlığı, karakter kodlaması vb.) yer aldığı alandır.
* `<title>`: Tarayıcı sekmesinde görünen başlığı belirler.
* `<body>`: Kullanıcının web sitesine girdiğinde ekranda gördüğü tüm görsel içeriklerin (metinler, resimler, butonlar vb.) yer aldığı kısımdır.

---

## 3. Sık Kullanılan Temel HTML Etiketleri

Web siteni zenginleştirmek için en çok kullanacağın etiketler şunlardır:

### Başlıklar (Headings)
Metinlerinizde hiyerarşi oluşturmak için `<h1>` ile `<h6>` arası etiketler kullanılır. `<h1>` en büyük ve en önemli başlığı belirtirken, `<h6>` en küçük başlıktır.

```html
<h1>Bu en büyük ana başlık (H1)</h1>
<h2>Bu alt başlık (H2)</h2>
```

### Paragraflar (Paragraphs)
Metin blokları oluşturmak için `<p>` etiketi kullanılır.

```html
<p>Bu bir paragraf cümlesidir. HTML öğrenmek oldukça keyiflidir!</p>
```

### Bağlantılar (Links)
Başka bir sayfaya veya web sitesine gitmek için `<a>` (anchor) etiketi kullanılır. `href` özelliği gitmek istenen adresi belirtir.

```html
<a href="https://github.com" target="_blank">GitHub'ı Ziyaret Et</a>
```

### Görseller (Images)
Sayfaya resim eklemek için `<img>` etiketi kullanılır. Kapanış etiketi yoktur. `src` görselin yolunu, `alt` ise görsel yüklenemediğinde çıkacak alternatif metni tanımlar.

```html
<img src="ornek-resim.jpg" alt="Örnek bir manzara resmi">
```

---

## 4. HTML'de Yorum Satırları 📝

Kod yazarken bazı satırların tarayıcı tarafından okunmamasını, sadece kendin veya diğer geliştiriciler için not bırakmak istemeni sağlayabilirsin. Bunun için şu yapı kullanılır:

```html
<!-- Bu bir HTML yorum satırıdır, ekranda görünmez. -->
```

---
