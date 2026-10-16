# Bag Stock Management (Web)

Bir çanta firması için geliştirilmiş ürün ve stok takip web uygulaması. Ürünler kategori sayfalarında listelenir; yetkili kullanıcı ürün ekleyebilir, güncelleyebilir, silebilir ve stok miktarını yönetebilir. Veritabanı yoktur, ürünler `web/products.json` dosyasında saklanır.

## Teknolojiler

- HTML, CSS, JavaScript
- Node.js, Express
- Multer (ürün görseli yükleme)
- JSON dosyası ile veri saklama

## Özellikler

- Ana sayfa ve kategori sayfaları: kadın çantaları, erkek çantaları, el çantaları, bel çantaları, cüzdanlar
- Yönetici paneli: ürün ekleme, güncelleme, silme, stok güncelleme
- REST API: `GET/POST /api/products`, `PUT /api/products/:id`, `PUT /api/products/:id/stock`, `DELETE /api/products/:id`

## Kurulum

Gereksinim: Node.js 18 veya üzeri.

```bash
git clone https://github.com/ahmetalpcinar/bag-stock-management-web.git
cd bag-stock-management-web
npm install
npm start
```

Uygulama `http://localhost:3000/html/index.html` adresinde açılır.

## Not

Yönetici girişi öğrenme amaçlı, istemci tarafında basit bir kontrolle yapılmaktadır (kullanıcı adı `admin`, şifre `12345678`). Gerçek bir ortamda kullanılmamalıdır; kimlik doğrulama sunucu tarafında yapılmalıdır.

## Ekran Görüntüleri

<img src="https://raw.githubusercontent.com/ahmetalpcinar/ahmetalpcinar/main/PNG/Images/imageBSIW1.png" alt="Ana sayfa" width="420"> <img src="https://raw.githubusercontent.com/ahmetalpcinar/ahmetalpcinar/main/PNG/Images/imageBSIW2.png" alt="Giriş sayfası" width="420">
<img src="https://raw.githubusercontent.com/ahmetalpcinar/ahmetalpcinar/main/PNG/Images/imageBSIW3.png" alt="Ürün ve stok yönetimi" width="420"> <img src="https://raw.githubusercontent.com/ahmetalpcinar/ahmetalpcinar/main/PNG/Images/imageBSIW4.png" alt="Kurulum" width="420">
