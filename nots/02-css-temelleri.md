# 02 - CSS Temelleri

## Amaç
CSS sayfanın görünümünü belirler. Renk, boşluk, yazı tipi ve yerleşim burada başlar.

## Temel Noktalar
- Seçiciler ile eleman hedeflenir.
- Box model, margin, border, padding ve content'ten oluşur.
- `display` değeri yerleşimi değiştirir.
- `color`, `background`, `font-size`, `font-family` temel görünümü oluşturur.
- `width`, `height`, `max-width` ve `gap` düzen için önemlidir.

## Box Model Kısa Not
Bir elemanın gerçek kapladığı alan sadece içerik değil, kenarlık ve boşluklarla birlikte düşünülmelidir.

## Mini Örnek
```css
.card {
  max-width: 320px;
  padding: 16px;
  margin: 20px auto;
  border: 1px solid #ddd;
  background: white;
}
```

## Sık Yapılan Hata
- Box model'i hesaba katmadan genişlik vermek.
- Gereksiz fazla seçici kullanmak.
- Boşlukları tutarsız bırakmak.

## Sonraki Adım
CSS temelleri oturduktan sonra Grid ile düzenli sayfa yapıları kurmak daha kolay olur.