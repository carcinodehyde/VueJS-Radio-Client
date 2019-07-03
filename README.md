# Simple VueJS + Laravel Online Radio Client

## Requirement
* **PHP** >= 7.1.3
* OpenSSL PHP Extension
* PDO PHP Extension
* Mbstring PHP Extension
* Tokenizer PHP Extension
* XML PHP Extension
* Ctype PHP Extension
* JSON PHP Extension
* **Node** >= 8.9.4
* **NPM** >= 5.6.0

## How to Install
1. Install Dependencies
```bash
npm install
```
2. Add write permission (Unix)
```bash
chmod -R go+w storage bootstrap/cache
```
3.  Compile Static Asset
```bash
## for Development
npm run dev

## for Production
npm run prod

## for Development with HMR (Hot Module Replacement)
npm run hot
```

## Using Docker Compose

### For Development
* Create and start Container
```bash
docker-compose up -d dev
```

* Enter workspace
```bash
docker-compose exec dev bash
```

* Install Depencies
```
composer install
npm install
```

* Compile Static Asset
```bash
## Single run compile
npm run dev

## or watch and compile every change
npm run watch

## or using Hot Module Replacement
npm run hot
```
* Open browser, goto [http://localhost:8888](link)

### For Production
* Create and start Container
```
docker-compose up -d prod
```

* Open browser, goto [http://localhost:88](link)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

[laravel]: https://laravel.com
[coreui]: https://coreui.io
[axios]: https://github.com/axios/axios
[jquery]: https://jquery.com/
[lodash]: https://lodash.com/
[moment]: https://momentjs.com/
[vue-router]: https://router.vuejs.org/
[vuex]: https://vuex.vuejs.org/
[vue-sweatalert2]: https://github.com/avil13/vue-sweetalert2
[vue-notification]: http://vue-notification.yev.io/
[vue-loading-spinner]: https://nguyenvanduocit.github.io/vue-loading-spinner/
[docker-compose]: https://docs.docker.com/compose/
[offline-plugin]: https://github.com/NekR/offline-plugin
[workbox]: https://developers.google.com/web/tools/workbox/
[laravel-page-speed]: https://github.com/renatomarinho/laravel-page-speed
