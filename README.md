# JavaScript Kodunu Konsolda ve Bookmarklet Olarak Kullanma Rehberi

Bu rehber, bir JavaScript kodunu hem tarayıcı konsolunda çalıştırmak hem de bir bookmarklet (yer imi) olarak ekleyip kullanmak için gerekli adımları içerir.

---

## 1. Konsolda JavaScript Kodu Çalıştırmak

1. Web tarayıcınızda istediğiniz siteyi açın.
2. Klavyeden `F12` tuşuna veya sağ tıklayıp **İncele/Inspect** seçeneğine tıklayın.
3. **Console** (Konsol) sekmesine geçin.
4. Aşağıdaki gibi JavaScript kodunuzu yapıştırıp `Enter`’a basın:

```javascript
alert("Merhaba, bu bir konsol komutudur!");
console-enter dosyası içerisindeki kodu kopyalayıp çalıştırabilirsiniz.
```

---

## 2. Bookmarklet (Yer İmi) Olarak JavaScript Kodu Kullanmak

1. JavaScript kodunuzu tek satıra indirgeyin ve başına `javascript:` ekleyin.
   - **Çok satırlı kodları** tek satıra dönüştürmek için tüm satır sonlarını kaldırın veya uygun şekilde `;` ile birleştirin.
2. Örnek bookmarklet kodu:

```javascript
javascript:alert("Merhaba, bu bir bookmarklet!");
```

3. Tarayıcıda yer imleri çubuğunu gösterin.
4. Yeni bir yer imi ekleyin:
    - Ad: İstediğiniz bir isim (ör: Konsol JS)
    - URL: Hazırladığınız bookmarklet kodunu buraya yapıştırın.
5. Artık herhangi bir sayfadayken bu yer imine tıklayarak kodunuzu çalıştırabilirsiniz.
6. bookmark dosyasındaki kodu url kısmına yapıştırarak kodu kullanabilirsiniz.

---

## Örnek: Konsol Kodunu Bookmarklet’e Çevirme

**Konsoldaki Kod:**
```javascript
document.body.style.background = "yellow";
```

**Bookmarklet’e Çevrilmiş Hali:**
```javascript
javascript:document.body.style.background='yellow'
```

---

## Dikkat Edilmesi Gerekenler

- Bookmarklet kodları genellikle kısa ve tek satır olmalıdır.
- `<script>` etiketiyle başlamayın, sadece `javascript:` ile başlayın.
- Kapsamlı kodlar için kodunuzu minimize edebilirsiniz (örn. https://javascript-minifier.com/).

---

## Faydalı Kaynaklar

- [Bookmarklet Nedir? (Wikipedia)](https://tr.wikipedia.org/wiki/Bookmarklet)
- [JavaScript Minifier](https://javascript-minifier.com/)

---

**Not:** Modern tarayıcılarda bazı güvenlik kısıtlamaları nedeniyle bazı JavaScript kodları çalışmayabilir.
