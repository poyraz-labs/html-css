# 04 - Grid İleri

## Amaç
Grid yapısını daha esnek ve responsive hale getirmek için gelişmiş özellikleri kullanmak.

## Temel Noktalar
- `fr` birim ile alanı oranlı paylaştırırsın.
- `repeat()` tekrar eden kolonları kısa yazmayı sağlar.
- `minmax()` minimum ve maksimum aralık verir.
- `auto-fit` ve `auto-fill` responsive grid kurmada yardımcı olur.
- `justify-content` ve `align-content` tüm grid alanını hizalar.

## Responsive Mantık
Küçük ekranda az sütun, büyük ekranda daha fazla sütun göstermek için grid yapısı akıcı olmalıdır. Bunun için esnek kolon tanımları kullanılır.

## Mini Örnek
```css
.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
  gap: 20px;
}
```

## Sık Yapılan Hata
- Sabit piksel kolonlara fazla bağımlı kalmak.
- Responsive davranışı sadece media query ile çözmeye çalışmak.
- `minmax` kullanmadan çok kırılgan layout kurmak.

## Sonraki Adım
Bu yapı oturduktan sonra Grid içine animasyon eklemek daha anlamlı olur.