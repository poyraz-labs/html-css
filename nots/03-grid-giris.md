# 03 - Grid Giriş

## Amaç
CSS Grid, iki boyutlu yerleşim kurmak için kullanılır. Satır ve sütunları birlikte kontrol etmeyi sağlar.

## Temel Noktalar
- Grid sadece container üzerinde başlar.
- `display: grid` ile aktif olur.
- `grid-template-columns` sütunları belirler.
- `grid-template-rows` satırları belirler.
- `gap` elemanlar arasındaki boşluğu ayarlar.

## Grid Mantığı
Grid container, içindeki elemanları otomatik olarak satır ve sütunlara yerleştirir. Bu yüzden kart yapıları ve sayfa düzenleri için çok uygundur.

## Mini Örnek
```css
.grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 16px;
}
```

## Sık Yapılan Hata
- `display: grid` vermeden grid özellikleri kullanmak.
- Sütun sayısını ihtiyaca göre planlamamak.
- Boşlukları sonradan zorla düzeltmeye çalışmak.

## Sonraki Adım
Grid temeli oturduktan sonra responsive yapı kurmak için `fr`, `repeat` ve `minmax` gibi özelliklere geçilir.