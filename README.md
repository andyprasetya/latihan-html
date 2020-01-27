# Latihan HTML dan Bulma CSS
Latihan HTML untuk Prakerin SMK TKJ/RPL

### Petunjuk Inisiasi
1. Install [Git](https://git-scm.com/).
2. Install [NodeJS](https://nodejs.org/en/download/).
3. Aktifkan Node.js _command prompt_, dan arahkan _working directory_ ke sebuah direktori kosong (misal: `D:\prakerin`):
```
C:\Users\USER>d:
D:\>cd prakerin
```
4. Clone repositori ini. Ada 2 cara, yaitu dengan menggunakan perintah `git clone ...`:
Jika Anda memilih cara ini, maka buat sebuah direktori baru (misal: `D:\prakerin\latihan-html-bulma`) sebagai langkah awal:
```
D:\prakerin>mkdir latihan-html-bulma
D:\prakerin>cd latihan-html-bulma
D:\prakerin\latihan-html-bulma>git clone https://github.com/andyprasetya/latihan-html.git .
```
atau dengan menggunakan perintah `npx degit ...`:
```
D:\prakerin>npx degit andyprasetya/latihan-html latihan-html-bulma
D:\prakerin>cd latihan-html-bulma
```
5. Install _dependencies_:
```
D:\prakerin\latihan-html-bulma>npm install
D:\prakerin\latihan-html-bulma>npm install bulma --save
```
6. Aktifkan VisualStudio Code:
```
D:\prakerin\latihan-html-bulma>code .
```
7. Import `bulma.sass` dari `node_modules/bulma` pada file `src/main.js`:
```javascript
import '../node_modules/bulma/bulma.sass';
...
```
8. Simpan perubahan dan jalankan perintah:
```
D:\prakerin\latihan-html-bulma>npm run dev
```
Selanjutnya, buka `http://localhost:5000` pada browser untuk memulai latihan HTML + Bulma CSS.
