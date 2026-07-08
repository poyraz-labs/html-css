# 05 - Animasyon Giriş

## Amaç
CSS animasyonları sayfaya hareket ve akıcılık ekler. İlk adım çoğunlukla `transition` ile başlar.

## Temel Noktalar
- `transition` bir durum değişimini yumuşatır.
- Hover ve focus efektlerinde çok kullanılır.
- Renk, gölge, dönüş ve boyut geçişleri eklenebilir.
- Kısa ve sade geçişler daha temiz görünür.

## Transition Mantığı
Bir eleman normal durumdan başka bir duruma geçtiğinde animasyonlu görünmesini sağlar. En çok butonlar, kartlar ve linklerde kullanılır.

## Mini Örnek
```css
.button {
  transition: background-color 0.3s ease, transform 0.3s ease;
}

.button:hover {
  transform: translateY(-2px);
}
```

## Sık Yapılan Hata
- Her şeyi aynı anda animasyonlu yapmak.
- Süreyi fazla uzun tutmak.
- Gereksiz ağır efektler kullanmak.

## Sonraki Adım
Transition temelini öğrendikten sonra gerçek animasyonlar için `@keyframes` yapısına geçilir.