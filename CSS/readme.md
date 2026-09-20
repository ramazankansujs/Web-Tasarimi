# CSS Temelleri Rehberi 

Hoş geldin! Bu rehber, HTML ile oluşturduğun web sayfalarına stil vermek, tasarlamak ve onları görsel açıdan zenginleştirmek için kullanılan **CSS (Cascading Style Sheets)** dilini en temel ve anlaşılır şekilde öğrenmen için hazırdır.

---

## 1. CSS Nedir? (Cascading Style Sheets)

* **Tanım:** CSS, HTML elemanlarının ekranda nasıl görüneceğini belirleyen stil/biçimlendirme dilidir.
* **Görevi:** Tasarımın estetik yönünü yönetir. Renkler, yazı tipleri (fontlar), boyutlar, boşluklar, hiza ve sayfa düzeni (layout) CSS ile ayarlanır.
* **Çalışma Mantığı:** "Seçiciler" (Selectors) ile hangi HTML elemanını değiştirmek istediğini belirtir, ardından "Özellik" (Property) ve "Değer" (Value) çiftleriyle stili uygularsın.

---

## 2. CSS Yazım Kuralları (Sözdizimi / Syntax)

CSS kodları temel olarak şu yapıdan oluşur:

```css
seçici {
    özellik: değer;
}
```

**Örnek:**

```css
h1 {
    color: blue;
    font-size: 24px;
}
```

* **Seçici (Selector):** Stil verilecek HTML elemanıdır (Örn: `h1`).
* **Özellik (Property):** Neyi değiştirmek istediğindir (Örn: `color`, `font-size`).
* **Değer (Value):** Özelliğin alacağı yeni durumdur (Örn: `blue`, `24px`).

---

## 3. CSS’i HTML'e Eklemenin 3 Yolu

### 1. Harici CSS (External) — *En Çok Tercih Edilen*
Stil kodları `.css` uzantılı ayrı bir dosyada yazılır ve HTML'deki `<head>` kısmına eklenir.

```html
<head>
    <link rel="stylesheet" href="style.css">
</head>
```

### 2. Dahili CSS (Internal)
HTML dosyasının içindeki `<head>` bölümüne `<style>` etiketleri arasına yazılır.

```html
<head>
    <style>
        body {
            background-color: lightgray;
        }
    </style>
</head>
```

### 3. Satır İçi CSS (Inline)
Doğrudan HTML etiketinin içine `style` niteliği verilerek yazılır. *(Tavsiye edilmez)*

```html
<p style="color: red;">Bu kırmızı bir yazıdır.</p>
```

---

## 4. Temel CSS Seçicileri (Selectors)

HTML elemanlarını hedeflemek için 3 ana seçici kullanılır:

1. **Etiket Seçici (Element Selector):** Tüm ilgili HTML etiketlerini seçer.
   ```css
   p {
       color: green;
   }
   ```
2. **Sınıf Seçici (Class Selector):** Belirli gruba ait elemanları seçer. HTML'de `class="kutucuk"` olanları CSS'te `.` (nokta) ile hedefle.
   ```css
   .kutucuk {
       background-color: yellow;
   }
   ```
3. **Kimlik Seçici (ID Selector):** Tek ve benzersiz bir elemanı seçer. HTML'de `id="ana-baslik"` olanı CSS'te `#` (kare) ile hedefle.
   ```css
   #ana-baslik {
       font-weight: bold;
   }
   ```

---

## 5. Sık Kullanılan Temel CSS Özellikleri

### Renk ve Arka Plan
```css
body {
    background-color: #f0f0f0; /* Arka plan rengi */
}

h1 {
    color: #333333; /* Metin rengi */
}
```

### Yazı Tipleri ve Metin Özellikleri
```css
p {
    font-family: Arial, sans-serif; /* Yazı tipi */
    font-size: 16px;                 /* Yazı boyutu */
    text-align: center;              /* Metni ortala (left, right, center, justify) */
}
```

### Kutu Modeli (Box Model: Margin ve Padding)
Web sayfasındaki her eleman bir kutudan oluşur.

```css
div {
    width: 300px;           /* Genişlik */
    height: 150px;          /* Yükseklik */
    padding: 20px;          /* İÇ boşluk (İçerik ile kenarlık arası) */
    margin: 10px;           /* DIŞ boşluk (Elemanın diğer elemanlarla arası) */
    border: 2px solid black;/* Kenarlık (Kalınlık, Tip, Renk) */
}
```

---

## 6. CSS'de Yorum Satırları 📝

Kod içine açıklama veya not eklemek istediğinde şu yapıyı kullanırsın:

```css
/* Bu bir CSS yorum satırıdır, tarayıcı tarafından çalıştırılmaz. */
```
