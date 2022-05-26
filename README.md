### Family-MD Reupload

Re upload Dari https://github.com/Fokusdotid/Family-MD

Yang Di Re upload ulang Dengan Tambahan node_modules

langsung Bisa Di pakai Tanpa Harus Mendownload node_modules nya

#### UNTUK TERMUX

```
$ pkg update && upgrade
$ apt update && upgrade
$ pkg install nodejs
$ pkg install ffmpeg
$ pkg install imagemagick
$ pkg install git
$ git clone https://github.com/hirohito-xyz/Family-Md-Nm
$ cd Family-Md-Nm
$ node main
```
---------------------------

WhatsApp Bot Multi Device

---------------------------

## Arguments `node . [--options] [<session name>]` 

### `--session <nama file>`

menggunakan session dari nama file yang berbeda, default `session.data.json`

contoh nama file `family.json` maka penggunaannya `node . --session 'family'`

### `--prefix <prefix>`

* `prefixes` dipisahkan oleh masing-masing karakter
Setel awalan

### `--server`

Digunakan untuk [heroku](https://heroku.com/) atau pindai melalui situs web

### `--db <url mongodb kamu>`

Buka file package.json dan isikan url mongodb kamu di bagian `mongo: --db url mongodb`!

### `--db <json-server-url>`

menggunakan db eksternal alih-alih db lokal, **disarankan** menggunakan mongodb

contoh server dengan mongodb `mongodb+srv://<username>:<password>@name-of-your-db.thhce.mongodb.net/myFirstDatabase?retryWrites=true&w=majority`

contoh server dengan repl `https://json-server.nurutomo.repl.co/`

kode: `https://repl.it/@Nurutomo/json-server`

`node . --db 'https://json-server.nurutomo.repl.co/'`

server harus memiliki spesifikasi seperti ini

#### GET

```http
GET /
Accept: application/json
```

#### POST

```http
POST /
Content-Type: application/json

{
 data: {}
}
```

### `--big-qr`

Jika qr unicode kecil tidak mendukung

### `--img`

Aktifkan pemeriksa gambar melalui terminal

### `--test`

**Development** Testing Mode

### `--trace`

```js
conn.logger.level = 'trace'
```

### `--debug`

```js
conn.logger.level = 'debug'
```

---------------------------

##### Special Thanks to
[![Nurutomo](https://github.com/Nurutomo.png?size=100)](https://github.com/Nurutomo)
[![BochilGaming](https://github.com/BochilGaming.png?size=100)](https://github.com/BochilGaming)

##### Penulis Ulang
[![Fokus ID](https://github.com/fokusdotid.png?size=100)](https://github.com/fokusdotid)

##### Si Penambah node_modules
[![hirohito xyz](https://github.com/hirohito-xyz.png?size=100)](https://github.com/hirohito-xyz)


###### Collaborator

[![RHns](https://github.com/imrhns.png?size=100)](https://github.com/imrhns)
[![M imam Adi](https://github.com/adi-officiall.png?size=100)](https://github.com/adi-officiall)
[![Aniq](https://github.com/aniq12.png?size=100)](https://github.com/aniq12)
