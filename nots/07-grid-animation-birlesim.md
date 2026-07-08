# 07 - Grid + Animation Birleşimi

## Amaç
Grid yerleşimi ile animasyonu birlikte kullanarak daha canlı ve düzenli arayüzler oluşturmak.

## Temel Noktalar
- Grid sayfa yapısını düzenler.
- Animasyon dikkat çekici küçük hareketler ekler.
- Kartlar, galeri alanları ve feature bölümlerinde iyi çalışır.
- Önce layout, sonra motion düşünmek daha temiz sonuç verir.

## Birlikte Kullanım Mantığı
Grid ile elemanların yerini sabitlersin, animasyon ile bu elemanların girişini veya hover etkisini güçlendirirsin.

## Mini Örnek
```css
.features {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 16px;
}

.feature-card {
  animation: fadeUp 0.5s ease-out both;
}
```

## Sık Yapılan Hata
- Animasyonu düzenin önüne koymak.
- Grid'i çok sıkışık bırakmak.
- Her kartta farklı ve gereksiz hareket kullanmak.

## Sonraki Adım
Bu birleşim küçük bir proje akışında daha net görülür; sonraki not bunun için iyi bir başlangıç olur.