# HTML Metin Biçimlendirme Temelleri

##  Temel Sayfa Yapısı ve Başlıklar

*   `<body bgcolor="lightblue">`: Sayfanın arka plan rengini açık mavi (lightblue) yapar.
*   `<h1>...</h1>`: En büyük başlık etiketidir. Sayfanın ana başlıklarını belirtmek için kullanılır.
*   `<p align="center">...</p>`: Paragraf (`<p>`) etiketidir. `align="center"` niteliği ile metin sayfaya ortalanmıştır.
*   `<hr />`: Sayfaya yatay bir çizgi çeker. Konuları birbirinden ayırmak için kullanılır.
*   `<br>`: Alt satıra geçmek için kullanılır.

---

##  Metin Biçimlendirme Etiketleri

HTML'de metinleri görsel olarak şekillendirmek için çeşitli etiketler bulunur:

### Kalın ve İtalik Yazılar
*   **`<b>` (Bold)**: Metni görsel olarak **kalın** yapar.
*   **`<strong>`**: Metnin **önemli** olduğunu tarayıcıya ve arama motorlarına bildirir, görsel olarak kalın yapar.
*   **`<i>` (Italic)**: Metni görsel olarak *italik (eğik)* yapar.
*   **`<em>` (Emphasis)**: Okunurken üzerinde durulması gereken, *vurgulanmış* metinleri ifade eder, görsel olarak italik yapar.

### Altı ve Üstü Çizili Yazılar
*   **`<u>` (Underline)**: Metnin <u>altını çizer</u>.
*   **`<ins>` (Inserted)**: Belgeye sonradan eklenmiş (yeni) veriyi temsil eder, görsel olarak altı çizilidir.
*   **`<del>` (Deleted)**: Belgeden silinmiş (eski) veriyi temsil eder, metnin <del>üstünü çizer</del>.
*   **`<s>` ve `<strike>`**: Metnin üstünü çizer. (Not: `<strike>` HTML5 ile kullanımdan kalkmış eski bir etikettir, yerine `<del>` veya `<s>` tercih edilir).

### Boyutlandırma ve İşaretleme
*   **`<big>`**: Metni normalden <big>büyük</big> yazar (HTML5'te desteklenmez, CSS önerilir).
*   **`<small>`**: Telif hakkı, alt bilgi veya konsol komutları gibi detaylar için <small>küçük</small> yazılar oluşturur.
*   **`<mark>`**: Metnin arka planını sarıya boyayarak <mark>işaretlenmiş/fosforlu</mark> gibi görünmesini sağlar.

### Alıntılar
*   **`<q>` (Quote)**: Kısa, satır içi alıntılar için kullanılır. Metni otomatik olarak tırnak (" ") içerisine alır.
*   **`<cite>`**: Bir eserin veya kaynağın adını belirtmek (atıf yapmak) için kullanılır. Genellikle italik görünür.

### Alt ve Üst Simgeler (Matematik & Kimya)
*   **`<sub>` **: Alt simge oluşturur. 
    *   *Örnek:* H<sub>2</sub>O (Kimyasal formüller veya log<sub>2</sub> gibi matematiksel ifadeler için).
*   **`<sup>` **: Üst simge oluşturur. 
    *   *Örnek:* E=MC<sup>2</sup> veya 2<sup>3</sup> = 8 gibi üslü sayılar için.

---

##  Örnek Kod Blokları

```html
<!DOCTYPE html>
<html>
<head>
    <title>Merhaba</title>
</head>
    <body bgcolor="lightblue">
        <h1>Web Geliştirme Temelleri</h1>
        
        <b>Kalın yazı</b> <br>
        <i>İtalik yazı</i> <br>
        <u>Altı çizili yazı</u> <br>
        
        H <sub>2</sub>O <br>
        E=MC<sup>2</sup>
    </body>
</html>
```
