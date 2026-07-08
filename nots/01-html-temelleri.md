# 01 - HTML Temelleri

## Amaç
HTML sayfanın iskeletini kurar. CSS gelmeden önce içerik yapısını doğru kurmak gerekir.

## Temel Noktalar
- Sayfa yapısı `html`, `head`, `body` ile kurulur.
- Başlıklar için `h1` - `h6` kullanılır.
- Metin için `p`, bağlantı için `a`, liste için `ul` ve `li` kullanılır.
- Görsel için `img`, kapsayıcı için `div`, anlamlı bloklar için `section`, `article`, `header`, `footer` tercih edilir.
- Form yapılarında `label`, `input`, `button` birlikte düşünülür.

## Semantik Mantık
Semantik etiketler sayfanın ne içerdiğini anlatır. Bu hem okunabilirliği hem de erişilebilirliği artırır.

## Mini Örnek
```html
<header>
  <h1>Başlık</h1>
</header>

<main>
  <section>
    <p>Bu bir içerik alanı.</p>
  </section>
</main>
```

## Sık Yapılan Hata
- Her şeyi `div` ile kurmak.
- Başlık sırasını karıştırmak.
- Görsele alt metin eklememek.

## Sonraki Adım
HTML iskeleti oturduktan sonra aynı yapıyı CSS ile düzenlemek daha kolay olur.