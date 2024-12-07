# Agency

## Nasıl Kurulacak?

Uygulama dosyalarını yüklediğinizde veya githup üzerinden fork ettiğinizde bu uygulamayı kullanmaya başlayabilirsiniz. SUnucunuz veya bilgisayarınıza dosyaları indirdiğinizde, hangi klasör üzerinde çalışacak ise tüm dosyaları o klasöre taşıyın.

Sonrasında terminali açın ve terminal içerisinden proje klasörünüze gelin. Ardından komut satırından

```
npm init
```

komutunu vererek uygulamanın kurulmasını sağlayabilirsiniz. Sonrasında proje dizininiz içerisinde bir adet **.env** dosyası oluşturun. Bu dosya içerisinde üç önemli bilgi bulunacak.

```
APP_MONGO_DB_NAME=
APP_MONGODB_FULL_URL=mongodb://localhost:27017
APP_SESSION_SECRET_KEY=
```

## Installation

Öncelikle projeyi clonelayın.

```
git clone https://github.com/kaaniince/Agency.git
```

## Usage

Projeyi cloneladıktan sonra Visual Studio Code programında açınız.

Linux için:

```
cd Agency
code .
```

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Kullanılan Teknolojiler

Bu uygulama geliştirilirken kullanılan teknolojiler şunlardır.

- Node JS
- Express JS
- Node fs modülü
- Bcrypt
- Connect-mongo
- dotenv
- ejs
- express-fileupload
- express-session
- express-validator
- mongoose
- bootstrap
