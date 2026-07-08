# 06 - Animasyon İleri

## Amaç
`animation` ve `@keyframes` ile kendi hareket dizilerini tanımlamak.

## Temel Noktalar
- `@keyframes` animasyonun adımlarını tanımlar.
- `animation-duration` süreyi belirler.
- `animation-delay` gecikme ekler.
- `animation-timing-function` hareketin ritmini ayarlar.
- `animation-iteration-count` tekrar sayısını kontrol eder.

## Animation Mantığı
Transition sadece durum değişiminde çalışır. Animation ise baştan sona tanımlı bir hareket akışı oluşturur.

## Mini Örnek
```css
@keyframes fadeUp {
  from {
    opacity: 0;
    transform: translateY(12px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

.card {
  animation: fadeUp 0.6s ease-out both;
}
```

## Sık Yapılan Hata
- Çok fazla keyframe yazmak.
- Animasyonu gereksiz yere sürekli döndürmek.
- İçeriği okumayı zorlaştıran hızlı hareketler kullanmak.

## Sonraki Adım
Bu yapıdan sonra grid ile birleşen küçük arayüz örnekleri yapmak daha kolay olur.