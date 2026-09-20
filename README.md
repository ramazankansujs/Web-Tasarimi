



# HTML ve CSS Temelleri

Bu rehber, web geliştirmenin temel taşları olan **HTML** ve **CSS** hakkında temel bilgileri, farklarını ve örnek bir kod bloğunu içermektedir.

---

## 1. HTML Nedir? (HyperText Markup Language)

* **Tanım:** Bir web sayfasını ve içeriğini belirleyen işaretleme dilidir.
* **Görevi:** Web sitesinde hangi içeriğin bulunacağını söyler. Metinler, paragraflar, görseller, videolar, bağlantılar ve butonlar HTML kullanılarak sayfaya eklenir.
* **Çalışma Mantığı:** Etiketler (Tags) yardımıyla çalışır. Örneğin, bir başlık eklemek için `<h1>` etiketi kullanılırken, paragraf eklemek için `<p>` etiketi kullanılır.

---

## 2. CSS Nedir? (Cascading Style Sheets)

* **Tanım:** HTML ile oluşturulan içeriklerin nasıl görünmesini belirleyen stil dilidir.
* **Görevi:** Tasarımın estetik yönünü kontrol eder. Renkler, yazı tipleri (fontlar), boşluklar, arka planlar, hizalamalar ve sayfanın farklı ekran boyutlarına (telefon, bilgisayar, tablet) uyum sağlaması (**Responsive**) CSS ile yapılır.
* **Çalışma Mantığı:** Seçiciler (Selectors) ve özellikler (Properties) kullanılarak HTML elemanlarına stil verilir. Örneğin, bir başlığın rengini mavi yapmak veya yazı boyutunu değiştirmek CSS ile sağlanır.

---

## 3. Temel Farklar Tablosu

| Özellik | HTML | CSS |
| :--- | :--- | :--- |
| **Tam Adı** | Hyper Text Markup Language | Cascading Style Sheets |
| **Temel Amacı** | Sayfa yapısını ve içeriğini oluşturmak. | Sayfanın tasarımını ve görüntüsünü düzenlemek. |
| **Dil Türü** | İşaretleme Dili (Markup Language) | Biçimlendirme / Stil Dili (Style Sheet) |
| **Kullanım Alanı** | Metin, görsel, tablo vb. ekler. | Renk, font ve düzeni ayarlar. |

---

## 4 Yorum Satırı (Comment Line) 

### **1. Açıklaması**
Kodumuzdaki bölümlerin ne işe yaradığını unutmamak için yazdığımız ve programın çalışmasını kesinlikle etkilemeyen açıklama notlarıdır.

## **2. Kod Üzerinde Gösterimi:**
Hangi dili kullanırsan kullan, bilgisayar yorum satırı işaretini gördüğü an o satırın geri kalanını okumadan geçer.

### Örneğin:
* ``<!--- --->`` HTML kodları için kod olmayan, mevcut bölümün ne işe yaradığını not edebilmemizi sağlayan yorum satırıdır.
* ``/*   */`` CSS kodları için kod olmayan, mevcut bölümün ne işe yaradığını not edebilmemizi sağlayan yorum satırıdır.

## 5. Örnek HTML Kodu ve Açıklamaları

Aşağıdaki örnek kodu inceleyerek temel bir HTML sayfasının yapısını görebilirsiniz:
---

```html
<!DOCTYPE html>
<!-- Tarayıcıya bu belgenin HTML5 ile yazıldığını bildirir. -->

<style>  /* CSS kodlarını yazacağımız etikettir */
      h1{ /* H1 etiketini özelleştirebilmek için h1'i bildiriyoruz ve süslü parantez açıyoruz */
      color:red; /* Yazı rengini kırmızı yaptık */
      text-align: center; /* Yazıyı sitenin ortasında gözükmesini sağlıyoruz. */

} /* Yazdığımız özellikler bittiğinde süslü parantez ile kapatıyoruz */
</style>  <!-- CSS kodlarının bittiğini belirtiyoruz -->

<html>
      <!-- Tüm HTML kodlarının içine yazıldığı kök (ana) etikettir. -->

<head>
      <!-- Site içeriğinde görünmeyen ancak tarayıcı ve arama motorları için önemli olan arka plan bilgilerinin yazıldığı alandır. -->

<title>İlk HTML Sayfam</title>  
<!-- Tarayıcı sekmesindeki başlığı ve arama motoru sonuçlarında görünen sayfa başlığını belirler. -->

</head> 
<!-- Başlangıçtaki head etiketinin kapandığını belirtir. -->

<body> 
<!-- Kullanıcının web sitesine girdiğinde ekranda gördüğü tüm görsel içeriklerin (metinler, resimler, butonlar vb.) yer aldığı kısımdır. -->

    <h1>Merhaba Dünya</h1>    
    <!-- En büyük başlık etiketidir. -->
    
    <p>Merhaba Keçiborlu</p>    
    <!-- Paragraf oluşturmak için kullanılır. -->

</body> 
<!-- Body etiketinin burada bittiğini belirtir. -->

</html>    
<!-- HTML etiketinin burada bittiğini belirtir ve belgesi sonlandırır. -->
```
